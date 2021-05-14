# GT4500 : fireTorpedo() - Teszt tervek
- Egy teszt ami ellenőrzi, hogy alternatív TorpedoStore-okat használ felváltva az implementáció, mint a leírásban.
- Egy teszt ami ellenőrzi, hogy alternatív TorpedoStore-okat használatánál ha másik TorpedeStore-ban nincs lőszer, akkor használlja-e az előző lövésre használltat.
- Egy teszt ami ellenőrzi, hogy alternatív TorpedoStore-okat használatánál ha másik TorpedeStore-ban nincs lőszer, akkor használlja-e az előző lövésre használltat, amiben megint nincs lőszer és így nem sikerül tüzelni.
- Ha az egyik TorpedoStore üres, viszont a másik nem akkor is sikeres-e a tüzelés mindkettővel ALL módban.
- Megnézi, hogy újonnan létrehozva tényleg az első TorpedoStore-al lő a GT4500.