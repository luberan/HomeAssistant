# Home Assistant

Různé konfigurační soubory, automatizace a šablony související s chytrou domácností postavenou na platformě [Home Assistant](https://www.home-assistant.io/).

Repozitář slouží jako osobní sbírka YAML konfigurací pro automatizace, senzory, notifikace, ESPHome zařízení a další části domácí automatizace.

## Obsah repozitáře

V repozitáři se nachází například konfigurace pro:

- automatizace v Home Assistantu,
- ESPHome zařízení,
- měření spotřeby a výroby energie,
- vodoměry a detekci úniku vody,
- ovládání žaluzií,
- zavlažování,
- notifikace,
- řízení nabíjení auta,
- integrace zařízení jako Solax, Netatmo nebo Dražice.

## Příklady souborů

Mezi soubory v repozitáři patří například:

- `ESP32C2-Vodomer.yaml`
- `ESP32C3-Vodomer.yaml`
- `Notifikace-detekce-uniku-vody.yaml`
- `Notifikace-dokonceny-uklid.yaml`
- `Rizeni-nabijeni-auta-homeassistant.yaml`
- `Spusteni-cerpadel-zavlaha.yaml`
- `Vypnuti-cerpadel-pri-uniku-vody.yaml`
- `Vytazeni-zaluzii-pri-silnem-vetru.yaml`
- `Zatazeni-zaluzii-dopoledne.yaml`
- `Zatazeni-zaluzii-odpoledne.yaml`
- `Zatazeni-zaluzii-po-setmeni.yaml`
- `Zatazeni-zaluzii-pri-prichodu.yaml`
- `celkova_vyroba_energie.yaml`
- `drazice-okhe-smart-esp.yaml`
- `electricity_meter.yaml`
- `solax_homeassistant.yaml`

## Použití

Jednotlivé YAML soubory lze použít jako inspiraci nebo výchozí konfiguraci pro vlastní instalaci Home Assistantu.

Obecný postup:

1. Vyberte požadovaný YAML soubor.
2. Zkontrolujte názvy entit, zařízení, senzorů a služeb.
3. Upravte konfiguraci podle vlastní instalace Home Assistantu.
4. Vložte konfiguraci do odpovídající části Home Assistantu, například:
   - automatizace,
   - šablonové senzory,
   - ESPHome konfigurace,
   - skripty,
   - balíčky.
5. Ověřte konfiguraci v Home Assistantu.
6. Restartujte nebo znovu načtěte příslušnou část konfigurace.

## Upozornění

Konfigurace jsou přizpůsobené konkrétní domácnosti a konkrétním entitám v Home Assistantu. Před použitím je nutné upravit zejména:

- názvy entit,
- ID zařízení,
- názvy senzorů,
- služby,
- notifikační kanály,
- hodnoty prahů,
- časy spouštění,
- podmínky automatizací.

Bez těchto úprav nemusí konfigurace fungovat ve vaší instalaci.

## Doporučení

Před nasazením do produkční instalace doporučuji:

- zálohovat aktuální konfiguraci Home Assistantu,
- otestovat YAML syntaxi,
- ověřit konfiguraci přes nástroje Home Assistantu,
- nejprve spustit automatizace ručně,
- sledovat logy Home Assistantu po nasazení.

## Související odkazy

- [Home Assistant](https://www.home-assistant.io/)
- [Home Assistant Documentation](https://www.home-assistant.io/docs/)
- [ESPHome](https://esphome.io/)
- [YAML Syntax](https://yaml.org/)

## Licence

Tento repozitář je dostupný pod licencí MIT. Podrobnosti najdete v souboru [LICENSE](LICENSE).

## Autor

Repozitář spravuje [luberan](https://github.com/luberan).

Další informace a související obsah najdete také na webu:

<https://www.selfiehome.cz/>
