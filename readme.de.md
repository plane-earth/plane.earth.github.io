# PlaneEarthMap - Innovative Kartenprojektionen für das digitale Zeitalter

🌍 **[Deutsch](README.md)** | 🇺🇸 **[English](README.en.md)** | 🇪🇸 **[Español](README.es.md)**

## 🌍 Projektvision

PlaneEarthMap revolutioniert die digitale Kartographie durch alternative Erdprojektionen, die traditionelle Verzerrungen der Mercator-Projektion eliminieren. Unser GPU-beschleunigtes Rendering-System ermöglicht Echtzeit-Berechnungen komplexer Projektionsalgorithmen und bietet erstmals nahtlose bidirektionale Navigation.

## 🚀 Kernfeatures

- **🗺️ Alternative Projektionen**: Planare, konvexe und konkave Erdmodelle für verzerrungsfreie Darstellung
- **🔄 Nahtlose Navigation**: Weltweit erste bidirektionale Endlos-Navigation (Nord-Süd + Ost-West)
- **⚡ GPU-Rendering**: Hochperformante Echtzeit-Kartendarstellung mit externen GPU-Servern
- **🌐 Föderierte Architektur**: Dezentrale Karteninfrastruktur über ActivityPub-Protokoll
- **📱 ARM64-Optimiert**: Mobile-first Design für moderne Smartphone-Architektur
- **🔓 Open Source**: Community-getriebene Entwicklung unter AGPL v3 Lizenz

## ⚖️ Das Verzerrungsproblem

Traditionelle Kartenprojektionen führen zu erheblichen Größenverzerrungen:
- **Russland** erscheint etwa doppelt so groß wie **Afrika**, obwohl Afrika tatsächlich 1,3-mal größer ist
- **Grönland** wirkt größer als ganze Kontinente
- Diese Verzerrungen können zu **geopolitischen Missverständnissen** führen

PlaneEarthMap korrigiert diese Probleme durch flächentreue planare Projektionen.

## 🎓 Wissenschaftliche Fundierung

### Entwicklungspsychologische Basis
Studien der **Universität Illinois** zeigen, dass Kinder die Erde natürlicherweise als ebene Fläche wahrnehmen. PlaneEarthMap unterstützt diese natürliche räumliche Entwicklung durch:
- Altersgerechte planare Kartendarstellungen
- Graduellen Übergang zu komplexeren geometrischen Konzepten
- Förderung des geographischen Verständnisses ohne kognitive Dissonanz

## 🏗️ Technische Architektur

### Infrastruktur-Design
```
[Leistungsstarker VPS] ←→ [ARM64 Entwicklungsumgebung]
       ↓                          ↓
[Container-Services]        [Mobile Optimierung]
       ↓                          ↓
[GPU-Rendering-Pipeline]    [Cross-Platform-Tests]
```

### Kerntechnologien
- **Backend**: Container-basierte Mikroservices mit Docker/Podman
- **Frontend**: Progressive Web App mit WebGL-Rendering
- **Rendering**: GPU-beschleunigte Projektionsalgorithmen
- **Federation**: ActivityPub-Protokoll für dezentrale Kartendienste
- **Development**: Forgejo auf çō.de für kurze Git-URLs
- **Infrastructure**: ARM64-optimierte Build-Pipeline

## 🔧 Entwicklungsumgebung

### Domain-Architektur
```
plane.earth              # Öffentliche Präsenz
├── map.plane.earth     # PlaneEarthMap Anwendung
├── api.plane.earth     # REST-API Services
├── docs.plane.earth    # Entwicklerdokumentation
└── federation.plane.earth # ActivityPub-Hub

çō.de                   # Entwickler-Infrastruktur
├── planeearthmap-core  # Haupt-Engine Repository
├── planeearthmap-web   # Frontend Repository
└── algorithms          # Projektions-Algorithmen
```

### Vorteile der çō.de Domain
- **Ultra-kurze Git-URLs**: `git clone https://çō.de/planeearthmap-core`
- **Entwickler-freundlich**: Einfach zu tippen und zu merken
- **Unicode-Innovation**: Zeigt moderne Web-Standards

## 📊 Entwicklungsstatus

### Aktuelle Phase: Prototypentwicklung
Das Projekt befindet sich in der aktiven Entwicklungsphase mit funktionierender Infrastruktur:

✅ **Abgeschlossen:**
- Forgejo-Installation auf çō.de (stabil)
- Grundlegende Projektdokumentation
- Domain-Architektur etabliert
- ARM64-Entwicklungsumgebung

🔄 **In Entwicklung:**
- Planare Projektions-Engine
- GPU-Rendering-Pipeline
- Bidirektionale Navigation-Algorithmen

### Roadmap
1. **Phase 1**: Planare Projektions-Engine (aktuell)
2. **Phase 2**: Bidirektionale Navigation implementieren
3. **Phase 3**: Konvexe und konkave Projektionsmodelle
4. **Phase 4**: ActivityPub-Federation für dezentrale Services
5. **Phase 5**: Mobile Apps und Community-Tools

## 🌐 Innovative Navigation

### Bidirektionale Endlos-Navigation
PlaneEarthMap führt revolutionäre Navigationsmöglichkeiten ein:
- **Horizontale Kontinuität**: Wie bei OpenStreetMap (Ost-West)
- **Vertikale Kontinuität**: Erstmals auch Nord-Süd möglich
- **Nahtlose Übergänge**: Keine sichtbaren Kartengrenzen
- **Adaptive Koordinaten**: Dynamische Referenzpunkte

### Technische Innovation
- Topologische Transformation der Kartendaten
- GPU-basierte Echtzeit-Berechnungen
- Numerische Stabilität bei extremen Koordinaten
- Container-basierte parallele Datenverarbeitung

## 🎯 Zielgruppen

### Bildungssektor
- **Schulen**: Verzerrungsfreie Geographie-Ausbildung
- **Universitäten**: Wissenschaftliche Kartographie-Forschung
- **E-Learning-Plattformen**: Interactive Lernmaterialien

### Wissenschaft & Forschung
- **Kartographen**: Experimentelle Projektionsmethoden
- **Geographen**: Präzise Flächendarstellungen
- **Bildungspsychologen**: Altersgerechte räumliche Entwicklung

### Technische Community
- **Open-Source-Entwickler**: Community-getriebene Innovation
- **GPU-Computing-Experten**: Rendering-Optimierungen
- **Föderations-Enthusiasten**: Dezentrale Infrastrukturen

## 🔮 Zukunftsvision

### Dezentrale Kartographie
PlaneEarthMap etabliert eine neue Generation kartographischer Infrastrukturen:
- **Community-owned**: Keine zentralen Kontrolle durch Tech-Konzerne
- **Wissenschaftlich offen**: Reproduzierbare und transparente Algorithmen
- **Global verfügbar**: Föderierte Architektur für weltweite Resilienz

### Technologische Innovation
- **ARM64-Ökosystem**: Optimierung für die mobile Zukunft
- **KI-Integration**: Claude Code für automatisierte Entwicklung
- **Edge-Computing**: GPU-Rendering am Netzwerkrand

## 🤝 Mitmachen

PlaneEarthMap ist ein Open-Source-Projekt und lebt von Community-Beiträgen:

### Entwickler-Einstieg
```bash
# Repository klonen
git clone https://çō.de/planeearthmap-core

# Dokumentation lesen
curl -s https://docs.plane.earth

# Issues und Pull Requests auf çō.de
```

### Beitragsmöglichkeiten
- **Code**: Projektions-Algorithmen, GPU-Shader, Frontend
- **Dokumentation**: Tutorials, API-Docs, Wissenschaftliche Papers
- **Testing**: ARM64-Optimierung, Cross-Platform-Kompatibilität
- **Design**: UI/UX für komplexe kartographische Interfaces

## 📄 Lizenzierung

**Hauptlizenz**: AGPL v3 (GNU Affero General Public License)
- Schutz vor proprietärer Cloud-Service-Integration
- Sicherstellung der Community-Rückgabe
- Bildungsfreundlich und forschungskompatibel

**Modulare Lizenzierung**:
- **Kern-Engine**: AGPL v3
- **Plugin-APIs**: Apache 2.0
- **Dokumentation**: CC BY-SA 4.0

## 🌟 Alleinstellungsmerkmale

1. **Weltweit erste bidirektionale nahtlose Kartennavigation**
2. **GPU-beschleunigte alternative Erdprojektionen in Echtzeit**
3. **Entwicklungspsychologisch fundierte Kartendarstellung**
4. **Vollständig dezentrale, föderierte Karteninfrastruktur**
5. **ARM64-optimierte Mobile-Performance**
6. **Ultra-kurze Git-URLs durch Unicode-Domain**

---

*PlaneEarthMap: Revolutionäre Kartographie für eine präzisere Weltwahrnehmung*

**Kontakt**: [Entwickler-Informationen]  
**Hauptrepository**: https://çō.de  
**Projekt-Website**: https://plane.earth  
**Lizenz**: AGPL v3 (Open Source)
