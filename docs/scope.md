## AppAtlas Scope – Abgrenzung

**AppAtlas** ist ein kuratierter Katalog selbsthostbarer SaaS-Anwendungen.
Ziel ist es, einen plattformübergreifenden Vergleich zu ermöglichen – mit Fokus auf:

- **Self-Hosted Apps** mit UI/API
- **Multi-Target Deployment** (z. B. Docker, CapRover, YunoHost, Cloudron, Bitnami)
- **Open Source bevorzugt, aber nicht zwingend**

Wir grenzen uns bewusst von anderen Tool-Landschaften ab:

| Tooltyp                     | Beispiele                            | AppAtlas? | Warum nicht? |
|----------------------------|---------------------------------------|-----------|--------------|
| **System-Package-Manager** | `apt`, `yum`, `apk`, `dnf`, `brew`, `scoop` | ❌        | OS- & Tool-Zentriert, keine App-Metadaten |
| **Language-Package-Manager** | `pip`, `npm`, `cargo`, `gem`, `cran` | ❌        | Nur Libraries, keine selbsthostbaren Tools |
| **Dev-Env Tools**          | `asdf`, `nvm`, `rbenv`, `pyenv`       | ❌        | Version Switching für Devs, keine Apps |
| **Platform-App-Kataloge**  | CapRover, YunoHost, Umbrel, Cloudron  | ✅        | Enthalten installierbare, oft containerisierte Apps |
| **Multi-Target Builders**  | Bitnami, Helm Charts, Ansible Galaxy  | ✅        | Fokus auf Self-Hosting und Plattform-Vielfalt |
| **Container-Bundles**      | DockStarter, DietPi, CasaOS, Portainer Stacks | ✅        | Oft App-Fokus, teils UI-zentriert |
| **App Store Oberflächen**  | Nextcloud App Store, Grafana Plugins  | 🔸 teils  | Wenn Apps wirklich *Self-Hosted Units* sind |
| **Meta-Plattformen**       | NixOS/Nixpkgs                         | 🔸 optional | Nur, wenn Apps explizit hostbar & vergleichbar sind |

---

## Fokus von AppAtlas

- Apps mit Web-Oberfläche oder API (keine Libs, keine CLI-Tools)
- Vergleichbarkeit über Plattformen hinweg
- Zielgruppe: Self-Hoster, DevOps, digitale Souveränität
- Ergänzung statt Konkurrenz zu bestehenden Plattformen

AppAtlas = **Landkarte der installierbaren Apps**, kein Werkzeugkasten für Entwicklerlibs.

