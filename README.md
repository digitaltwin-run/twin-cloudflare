# twin-cloudflare — Digital Twin Cloudflare Simulator & Ingress Rules

`twin-cloudflare` to autonomiczny komponent Digital Twin symulujący działanie stref DNS Cloudflare, reguł proxying/tunneling oraz rejestrów rekordów A/AAAA/CNAME.

## Funkcje
- Emulacja zarządcy stref Cloudflare i automatycznej synchronizacji z Pleskiem (`cloudflaredns`).
- Sprawdzanie spójności rekordów DNS dla domen publicznych Subactora.
- Weryfikacja reguł `tunnel_mode` vs `public_ingress_mode`.
