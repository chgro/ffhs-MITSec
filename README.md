# M-ITSec - Management von Informationssicherheit, INF-V-IS001, BE-Sa-1, FS21

- [M-ITSec - Management von Informationssicherheit, INF-V-IS001, BE-Sa-1, FS21](#m-itsec---management-von-informationssicherheit--inf-v-is001--be-sa-1--fs21)
  * [Lerninhalte](#lerninhalte)
    + [Aufbau eines ISMS (Information Security Management System)](#aufbau-eines-isms--information-security-management-system-)
    + [Control Frameworks & IT Security Massnahmen](#control-frameworks---it-security-massnahmen)
    + [Prozesse und Incident Management](#prozesse-und-incident-management)
    + [Nachhaltiger Betrieb und Verbesserung](#nachhaltiger-betrieb-und-verbesserung)
    + [Business Continuity, Audit & Recht](#business-continuity--audit---recht)
- [1 Aufbau eines ISMS (Information Security Management System)](#1-aufbau-eines-isms--information-security-management-system-)
  * [Lernziele](#lernziele)
  * [Vorbereitung](#vorbereitung)
    + [CobIT - Control Objectives for Information and Related Technology](#cobit---control-objectives-for-information-and-related-technology)
    + [ISO/IEC 27001](#iso-iec-27001)
    + [ITIL - Information Technology Infrastructure Library](#itil---information-technology-infrastructure-library)
    + [BSI - Bundesamt für Sicherheit in der Informationstechnik (Deutschland)](#bsi---bundesamt-f-r-sicherheit-in-der-informationstechnik--deutschland-)
    + [Common Criteria](#common-criteria)
    + [OSSTMM](#osstmm)
    + [FIPS 140](#fips-140)
    + [Verwendung mehrerer Standards](#verwendung-mehrerer-standards)
    + [Weitere Regelwerke](#weitere-regelwerke)
    + [Sicherheitsanforderungen](#sicherheitsanforderungen)
    + [Anforderungsklatalog](#anforderungsklatalog)
    + [IT-Sicherheitsbeauftragter](#it-sicherheitsbeauftragter)
      - [ISMS - Informationssicherheits-Managementsystem](#isms---informationssicherheits-managementsystem)
    + [Datenschutzbeauftragter](#datenschutzbeauftragter)
    + [Notfallteam](#notfallteam)
    + [Risikomanagement](#risikomanagement)
    + [IKS - Internes Kontrollsystem](#iks---internes-kontrollsystem)
    + [PDCA-Zyklus - Plan, Do, Check, Act](#pdca-zyklus---plan--do--check--act)
    + [Risikoanalyse](#risikoanalyse)
      - [Vorbereitung](#vorbereitung-1)
      - [Durchführung](#durchf-hrung)
    + [Risikoidentifikation](#risikoidentifikation)
    + [Risikobbewertung](#risikobbewertung)
      - [Risk Map](#risk-map)
    + [Business-Impact-Analyse](#business-impact-analyse)
    + [BCM - Business Continuity Managements](#bcm---business-continuity-managements)
    + [Strukturanalyse](#strukturanalyse)
    + [Sicherheitsstrategie und Sicherheitskonzept](#sicherheitsstrategie-und-sicherheitskonzept)
      - [Unternehmensstrategie](#unternehmensstrategie)
      - [Intelligente IT-Strategie](#intelligente-it-strategie)
      - [IT-Sicherheitsstrategie](#it-sicherheitsstrategie)
      - [IT-Sicherheitskonzept](#it-sicherheitskonzept)
      - [Kontrollmodell](#kontrollmodell)
    + [Managementsystem für IT-Sicherheit entwickeln](#managementsystem-f-r-it-sicherheit-entwickeln)
      - [Komponenten eines ISMS](#komponenten-eines-isms)
      - [MAnagementprinzipien](#managementprinzipien)
    + [Kontrolle der Überwachungsziele](#kontrolle-der--berwachungsziele)
    + [Auswertung von Sicherheitsvorfälle](#auswertung-von-sicherheitsvorf-lle)
    + [Überwachunngs und Detektionssysteme](#-berwachunngs-und-detektionssysteme)
    + [Beweissicherung](#beweissicherung)
    + [Eskalationsplan](#eskalationsplan)
    + [Personelle Massnahmen](#personelle-massnahmen)
      - [Personelle SIcherheitsmassnahmen](#personelle-sicherheitsmassnahmen)
      - [Sicherheitsweisungen](#sicherheitsweisungen)
      - [Regelmässige Sicherheitsschulungen](#regelm-ssige-sicherheitsschulungen)
      - [Austritt von Mitarbeitenden](#austritt-von-mitarbeitenden)
    + [Organisatorische Massnahmen](#organisatorische-massnahmen)
      - [Konzepte für die IT-Sicherheit](#konzepte-f-r-die-it-sicherheit)
      - [Weisungen](#weisungen)
      - [Verwaltung der Konzepte, Weisungen, Sicherheitsdokumente](#verwaltung-der-konzepte--weisungen--sicherheitsdokumente)
      - [Life-Cycle-Management](#life-cycle-management)
      - [Management-Tipps](#management-tipps)
  * [Präsenz](#pr-senz)
      - [Agenda](#agenda)
      - [Bedrohungen wandeln sich](#bedrohungen-wandeln-sich)
      - […sind aber auch inhärent](#-sind-aber-auch-inh-rent)
      - [Enemy Within…](#enemy-within-)
      - […and Outside](#-and-outside)
      - [Data Breaches](#data-breaches)
    + [Phasen einer Cyberattacke](#phasen-einer-cyberattacke)
      - [Marktplatz](#marktplatz)
    + [Vorgehen zum Aufbau eines ISMS](#vorgehen-zum-aufbau-eines-isms)
      - [ISIS12](#isis12)
        * [Übersicht](#-bersicht)
        * [Phase 0: Wieso benötige ich ein ISMS?](#phase-0--wieso-ben-tige-ich-ein-isms-)
        * [Phase 1: Initialisierung](#phase-1--initialisierung)
        * [Phase 2: Aufbau- & Ablauforganisation](#phase-2--aufbau----ablauforganisation)
        * [Phase 3: Entwicklung und Umsetzung](#phase-3--entwicklung-und-umsetzung)
        * [IAM](#iam)
    + [IT Sicherheitsstrategie](#it-sicherheitsstrategie)
      - [Definition](#definition)
      - [Strategiebaum](#strategiebaum)
        * [So viel wie nötig… …so wenig wie möglich](#so-viel-wie-n-tig---so-wenig-wie-m-glich)
      - [SWOT Analyse - Strengths, Weaknesses, Opportunities und Threats](#swot-analyse---strengths--weaknesses--opportunities-und-threats)
        * [Umsetzung](#umsetzung)
      - [Kritik an Strategischer Planung](#kritik-an-strategischer-planung)
    + [Risikoanalyse & Wahrnehmung von Risiken](#risikoanalyse---wahrnehmung-von-risiken)
      - [Definition](#definition-1)
      - [Wahrnehmung von Risiken](#wahrnehmung-von-risiken)
      - [Spezialfall: Cyber](#spezialfall--cyber)
      - [Risikoanalyse Schematischer Ablauf](#risikoanalyse-schematischer-ablauf)
      - [Risikobewertung](#risikobewertung)
      - [Identifizieren von Risiken](#identifizieren-von-risiken)
      - [Threat Model](#threat-model)
    + [Aufbauorganisation ISMS](#aufbauorganisation-isms)
      - [Übersicht](#-bersicht-1)
      - [Managementprinzipien](#managementprinzipien)
      - [Organisation](#organisation)
      - [Ressourcen](#ressourcen)
      - [Sicherheitskonzepte](#sicherheitskonzepte)
      - [Sicherheitskonzepte: Struktur](#sicherheitskonzepte--struktur)
      - [Prozesse](#prozesse)
    + [ISMS & PDCA](#isms---pdca)
    + [Personelle Massnahmen](#personelle-massnahmen-1)
      - [Mitarbeiter: ein Security Problem?](#mitarbeiter--ein-security-problem-)
      - [Security Awareness](#security-awareness)
      - [Wichtige HR Prozesse](#wichtige-hr-prozesse)
        * [Rollenbeschreibung](#rollenbeschreibung)
        * [Rekrutierung](#rekrutierung)
        * [Ausbildung](#ausbildung)
        * [Erkennen fehlender Stellvertretung](#erkennen-fehlender-stellvertretung)
        * [Schlüsselpersonen identifizieren](#schl-sselpersonen-identifizieren)
        * [Verletzung von Aufgabentrennung erkennen (Segregation of Duties)](#verletzung-von-aufgabentrennung-erkennen--segregation-of-duties-)
        * [Leistungsbeurteilung](#leistungsbeurteilung)
        * [Rollenwechsel und Austritt](#rollenwechsel-und-austritt)
          + [Nachbearbeitung](#nachbearbeitung)
- [2 Control Frameworks und IT Security Massnahmen](#2-control-frameworks-und-it-security-massnahmen)
          + [Lernziele](#lernziele-1)
  * [Vorbereitung](#vorbereitung-2)
    + [IT-Sicherheit](#it-sicherheit)
    + [Schutzziel Datensicherheit](#schutzziel-datensicherheit)
      - [Schutzziele (CIA)](#schutzziele--cia-)
      - [Vertraulichkeit (Confidentiality)](#vertraulichkeit--confidentiality-)
      - [Integrität (Integrity)](#integrit-t--integrity-)
        * [Realität](#realit-t)
        * [Aktualität](#aktualit-t)
        * [Authentizität](#authentizit-t)
      - [Verfügbarkeit (Availability)](#verf-gbarkeit--availability-)
      - [Verbindlichkeit](#verbindlichkeit)
        * [Authentizität](#authentizit-t-1)
        * [Rechtsgültigkeit](#rechtsg-ltigkeit)
        * [Nicht-Abstreitbarkeit](#nicht-abstreitbarkeit)
    + [Schutzziel Datenschutz](#schutzziel-datenschutz)
    + [Datensicherung](#datensicherung)
    + [Notfallvorsorge (Continuity Management, Contingency Management)](#notfallvorsorge--continuity-management--contingency-management-)
    + [Sicherheitsgefahren und -bedürfnisse](#sicherheitsgefahren-und--bed-rfnisse)
      - [Bedrohung, Verletzbarkeit und Risiko](#bedrohung--verletzbarkeit-und-risiko)
        * [Bedrohungen](#bedrohungen)
        * [Verletzbarkeit](#verletzbarkeit)
        * [Risiko](#risiko)
      - [Sicherheitsbedarf und Risikobereitschaft](#sicherheitsbedarf-und-risikobereitschaft)
        * [Güterabwägung](#g-terabw-gung)
      - [Sicherheitsmassnahmen](#sicherheitsmassnahmen)
      - [Sicherheit der Geschäftsprozesse](#sicherheit-der-gesch-ftsprozesse)
      - [Rolle der Informatik](#rolle-der-informatik)
      - [Sicherheitskriterien](#sicherheitskriterien)
        * [Organisatorische udn personelle Sicherheitskriterien](#organisatorische-udn-personelle-sicherheitskriterien)
    + [Anforderungen an die Sicherheit](#anforderungen-an-die-sicherheit)
      - [Externe Anforderungen](#externe-anforderungen)
      - [Interne Anforderungen](#interne-anforderungen)
      - [Sicherheitsanforderungen ermitteln](#sicherheitsanforderungen-ermitteln)
      - [Anfoderungskatalog](#anfoderungskatalog)
    + [Strukturanalyse und Schutzbedarfsstetllung](#strukturanalyse-und-schutzbedarfsstetllung)
      - [Netzplan erstellen](#netzplan-erstellen)
      - [Komplexität durch Gruppenbildung reduzieren](#komplexit-t-durch-gruppenbildung-reduzieren)
      - [Infrastrukturkomponeten erheben](#infrastrukturkomponeten-erheben)
      - [Geschäftskritische Anwendungen erfassen](#gesch-ftskritische-anwendungen-erfassen)
      - [Systemkomponeten pro Anwendung erheben](#systemkomponeten-pro-anwendung-erheben)
      - [Schutzbedarf für Anwendungen festlegen](#schutzbedarf-f-r-anwendungen-festlegen)
      - [Schutzbedarf für Systemkomponenten festlegen](#schutzbedarf-f-r-systemkomponenten-festlegen)
      - [Schutzbedarf für Kommunikationsverbindungen feststellen](#schutzbedarf-f-r-kommunikationsverbindungen-feststellen)
      - [Schutzbedarf für Räume festlegen](#schutzbedarf-f-r-r-ume-festlegen)
    + [Risiken analysieren, Schutzbedarf feststellen, Schwachsttellen aufdecken](#risiken-analysieren--schutzbedarf-feststellen--schwachsttellen-aufdecken)
  * [Präsenz](#pr-senz-1)
    + [Aufgabe 'Policy Templates'](#aufgabe--policy-templates-)
      - [SANS Policies: Kapitelstruktur](#sans-policies--kapitelstruktur)
      - [Frameworks: Übersicht](#frameworks---bersicht)
        * [Treiber](#treiber)
        * [Übersicht gebräuchlicher Frameworks](#-bersicht-gebr-uchlicher-frameworks)
        * [Center for Internet Security](#center-for-internet-security)
        * [National Institute of Standards and Technology](#national-institute-of-standards-and-technology)
        * [International Organization for Standardization](#international-organization-for-standardization)
        * [Information Security Forum](#information-security-forum)
      - [BSI](#bsi)
        * [BSI: Organisation](#bsi--organisation)
        * [BSI: IT Grundschutz Kataloge](#bsi--it-grundschutz-kataloge)
        * [BSI: Vernetzung der Kataloge](#bsi--vernetzung-der-kataloge)
        * [BSI: Bausteine](#bsi--bausteine)
        * [BSI: Gefährdungskataloge](#bsi--gef-hrdungskataloge)
        * [BSI: Massnahmenkataloge](#bsi--massnahmenkataloge)
      - [COBIT](#cobit)
        * [COBIT: Organisation](#cobit--organisation)
        * [COBIT: Geschichte](#cobit--geschichte)
        * [COBIT: Top-Down Vorgehen](#cobit--top-down-vorgehen)
        * [COBIT: Gesamtsicht](#cobit--gesamtsicht)
        * [COBIT: Prozesse](#cobit--prozesse)
        * [COBIT: Prozessbeschreibung](#cobit--prozessbeschreibung)
        * [COBIT 5: Vergleich zu Version 4](#cobit-5--vergleich-zu-version-4)
      - [ISO 27001](#iso-27001)
    + [ITIL](#itil)
      - [ITIL: Organisation](#itil--organisation)
      - [ITIL: Bücher und Inhaltsübersicht](#itil--b-cher-und-inhalts-bersicht)
      - [ITIL: Wallchart](#itil--wallchart)
    + [Frameworks anwenden: Risiken erkennen & Schutzbedarf bestimmen](#frameworks-anwenden--risiken-erkennen---schutzbedarf-bestimmen)
      - [Preventive & Detective Controls](#preventive---detective-controls)
      - [Gruppenarbeit](#gruppenarbeit)
          + [Nachbearbeitung](#nachbearbeitung-1)
- [3 Prozesse und Security Incident Management](#3-prozesse-und-security-incident-management)
          + [Lernziele](#lernziele-2)
  * [Vorbereitung](#vorbereitung-3)
  * [Präsenz](#pr-senz-2)
    + [Agenda](#agenda-1)
    + [Business Case](#business-case)
      - [Business Case - Details](#business-case---details)
      - [Business Case - Kapitelübersicht](#business-case---kapitel-bersicht)
    + [Prozessdesign](#prozessdesign)
      - [Definition 'Prozess'](#definition--prozess-)
      - [Prozess Design: Erste Schritte](#prozess-design--erste-schritte)
      - [Prozessdiagramm: Erstellung](#prozessdiagramm--erstellung)
      - [Prozessdiagramm: Visualisierung](#prozessdiagramm--visualisierung)
      - [Kontrollen](#kontrollen)
      - [Prozessdesign: Praxis](#prozessdesign--praxis)
      - [Prozessdesign: Abschluss](#prozessdesign--abschluss)
      - [Prozessdesign: Subjektivität](#prozessdesign--subjektivit-t)
      - [Gruppenarbeit: Prozessanalyse](#gruppenarbeit--prozessanalyse)
    + [RACI - Responsible Accountability Consulted Informed](#raci---responsible-accountability-consulted-informed)
      - [RACI: Einige Beobachtungen](#raci--einige-beobachtungen)
      - [Fallstudie: Erstellen eines RACI](#fallstudie--erstellen-eines-raci)
    + [Incident-, Problem & Change Management](#incident---problem---change-management)
      - [Begriffe](#begriffe)
      - [Incident Management](#incident-management)
      - [Problem Management](#problem-management)
      - [Incident oder Problem?](#incident-oder-problem-)
      - [Change Management](#change-management)
      - [IT Security Incident](#it-security-incident)
    + [Security Incident Response](#security-incident-response)
      - [CSIRT / CERT](#csirt---cert)
      - [CSIRT Einführung (1/2)](#csirt-einf-hrung--1-2-)
      - [CSIRT Einführung (2/2)](#csirt-einf-hrung--2-2-)
      - [Incident- und Krisenmanagement](#incident--und-krisenmanagement)
      - [Eskalationskriterien](#eskalationskriterien)
      - [Eskalationsstufen (1/4)](#eskalationsstufen--1-4-)
      - [Eskalationsstufen (2/4)](#eskalationsstufen--2-4-)
      - [Eskalationsstufen (3/4)](#eskalationsstufen--3-4-)
      - [Eskalationsstufen (4/4)](#eskalationsstufen--4-4-)
      - [Ausgewählte Kontrollen: Patch Management](#ausgew-hlte-kontrollen--patch-management)
        * [Patch Management Lifecycle & Process](#patch-management-lifecycle---process)
      - [Ausgewählte Kontrollen: IAM](#ausgew-hlte-kontrollen--iam)
      - [IAM als fortlaufender Prozess](#iam-als-fortlaufender-prozess)
      - [IAM Präventive Controls](#iam-pr-ventive-controls)
      - [Ausnahmeerkennung und Behandlung](#ausnahmeerkennung-und-behandlung)
  * [Nachbearbeitung](#nachbearbeitung-2)
- [4 Nachhaltiger Betrieb und Verbesserung](#4-nachhaltiger-betrieb-und-verbesserung)
          + [Lernziele](#lernziele-3)
  * [Vorbereitung](#vorbereitung-4)
  * [Präsenz](#pr-senz-3)
    + [Agenda](#agenda-2)
    + [Diskussion der Aufgabe 'Fallstudie Prozessdesign'](#diskussion-der-aufgabe--fallstudie-prozessdesign-)
      - [Lösen der Fallstudie](#l-sen-der-fallstudie)
        * [Musterlösung](#musterl-sung)
    + [IT Security Monitoring](#it-security-monitoring)
      - [SIEM: Begriff](#siem--begriff)
      - [SIEM: Eigenschaften](#siem--eigenschaften)
      - [SIEM Produkte](#siem-produkte)
      - [SIEM Produkte: Unruhiger Markt](#siem-produkte--unruhiger-markt)
    + [Big Picture: Logging & SIEM](#big-picture--logging---siem)
      - [Bottom-up Ansatz](#bottom-up-ansatz)
      - [Top-Down Ansatz: Threat Model](#top-down-ansatz--threat-model)
      - [Integration](#integration)
      - [Logmanagement](#logmanagement)
      - [Monitoring](#monitoring)
      - [Security Monitoring – Overview](#security-monitoring---overview)
      - [Incident Management](#incident-management-1)
    + [Risk- und Exception Management](#risk--und-exception-management)
      - [Weshalb Risk Management?](#weshalb-risk-management-)
      - [Definition](#definition-2)
      - [Risikoidentifikation](#risikoidentifikation-1)
      - [Risikobewertung](#risikobewertung-1)
      - [Risikosteuerung](#risikosteuerung)
      - [Risikosteuerung](#risikosteuerung-1)
      - [Risk Appetite](#risk-appetite)
      - [Risikosteuerung](#risikosteuerung-2)
      - [Risikokontrolle](#risikokontrolle)
    + [Maturity Model CMMI (Reifegradmessung)](#maturity-model-cmmi--reifegradmessung-)
      - [Definition CMMI](#definition-cmmi)
      - [Anwendung von CMMI](#anwendung-von-cmmi)
      - [Reifegrade](#reifegrade)
      - [Maturity Levelshttps://cmmiinstitute.com/learning/appraisals/levels](#maturity-levelshttps---cmmiinstitutecom-learning-appraisals-levels)
      - [Fallstudie CMMI](#fallstudie-cmmi)
      - [Fallstudie CMMI 'Benutzerberechtigungen'](#fallstudie-cmmi--benutzerberechtigungen-)
    + [Continuous Improvement: KPI](#continuous-improvement--kpi)
      - [Provide Actionable Risk Intelligence](#provide-actionable-risk-intelligence)
        * [Identify](#identify)
        * [Protect](#protect)
        * [Detect](#detect)
        * [Respond](#respond)
        * [Recover](#recover)
      - [Definition](#definition-3)
      - [Metrik – KPI – SLA](#metrik---kpi---sla)
      - [Bestimmen von KPI](#bestimmen-von-kpi)
      - [Definition sinnvoller KPI](#definition-sinnvoller-kpi)
      - [KPI: Beispiele](#kpi--beispiele)
      - [Einführen von KPI](#einf-hren-von-kpi)
      - [Auswerten / Rapportieren](#auswerten---rapportieren)
      - [Auswerten / Rapportieren](#auswerten---rapportieren-1)
      - [Metriken: Praxisbeispiele](#metriken--praxisbeispiele)
      - [KPI: Praxisbeispiel](#kpi--praxisbeispiel)
    + [Continuous Improvement: PDCA](#continuous-improvement--pdca)
      - [Geschichte](#geschichte)
      - [Plan – Do – Check – Act](#plan---do---check---act)
      - [Plan – Do](#plan---do)
        * [Plan](#plan)
        * [Do](#do)
      - [Check – Act](#check---act)
        * [Check](#check)
        * [Act](#act)
      - [PDCA: Standardize](#pdca--standardize)
  * [Nachbearbeitung](#nachbearbeitung-3)
- [5 Business Continuity, Audit & Recht](#5-business-continuity--audit---recht)
          + [Lernziele](#lernziele-4)
  * [Vorbereitung](#vorbereitung-5)
  * [Präsenz](#pr-senz-4)
  * [Nachbearbeitung](#nachbearbeitung-4)
- [Zusammenfassugen - IT Security Management](#zusammenfassugen---it-security-management)
  * [Kapitel 1 - Schutzziele und Schutzbedarf](#kapitel-1---schutzziele-und-schutzbedarf)
    + [Management-Tipps](#management-tipps-1)
  * [Kapitel 2 - Gesetze, Standards und Regelwerke](#kapitel-2---gesetze--standards-und-regelwerke)
    + [Management-Tipps](#management-tipps-2)
  * [Kapitel 3 - Sicherheitsanforderungen und -aufgaben](#kapitel-3---sicherheitsanforderungen-und--aufgaben)
    + [Management-Tipps](#management-tipps-3)
  * [Kapitel 4 - Methoden und Techniken](#kapitel-4---methoden-und-techniken)
    + [Management-Tipps](#management-tipps-4)
  * [Kapitel 5 - Sicherheitsstrategie und Sicherheitskonzept erstellen](#kapitel-5---sicherheitsstrategie-und-sicherheitskonzept-erstellen)
    + [Management-Tipps](#management-tipps-5)
  * [Kapitel 6 - Risiken analysieren, Schutzbedarf feststellen, Schwachstellen aufdecken](#kapitel-6---risiken-analysieren--schutzbedarf-feststellen--schwachstellen-aufdecken)
    + [Management-Tipps](#management-tipps-6)
  * [Kapitel 7 - Managementsystem für IT-Sicherheit entwickeln](#kapitel-7---managementsystem-f-r-it-sicherheit-entwickeln)
    + [Management-Tipps](#management-tipps-7)
  * [Kapitel 8 - Sicherheits- und Notfallmassnahmen entwickeln](#kapitel-8---sicherheits--und-notfallmassnahmen-entwickeln)
    + [Management-Tipps](#management-tipps-8)
  * [Kapitel 9 - Sicherheitsmassnahmen aufeinander abstimmen](#kapitel-9---sicherheitsmassnahmen-aufeinander-abstimmen)
    + [Management-Tipps](#management-tipps-9)
  * [Kapitel 10 - Personelle Massnahmen planen und umsetzen](#kapitel-10---personelle-massnahmen-planen-und-umsetzen)
    + [Management-Tipps](#management-tipps-10)
  * [Kapitel 11 - Organisatorische Massnahmen planen und umsetzen](#kapitel-11---organisatorische-massnahmen-planen-und-umsetzen)
    + [Management-Tipps](#management-tipps-11)
  * [Kapitel 12 - Technische Massnahmen planen und umsetzen](#kapitel-12---technische-massnahmen-planen-und-umsetzen)
    + [Management-Tipps](#management-tipps-12)
  * [Kapitel 13 - Bereichsübergreifende Massnahmen](#kapitel-13---bereichs-bergreifende-massnahmen)
    + [Management-Tipps](#management-tipps-13)
  * [Kapitel 14 - Sicherheitsmassnahmen und -aktivitäten überwachen](#kapitel-14---sicherheitsmassnahmen-und--aktivit-ten--berwachen)
    + [Management-Tipps](#management-tipps-14)
  * [Kapitel 15 - Audits und Tests organisieren und durchführen](#kapitel-15---audits-und-tests-organisieren-und-durchf-hren)
    + [Management-Tipps](#management-tipps-15)
  * [Kapitel 16 - Wirksamkeit und Wirtschaftlichkeit der Massnahmen kontrollieren](#kapitel-16---wirksamkeit-und-wirtschaftlichkeit-der-massnahmen-kontrollieren)
    + [Management-Tipps](#management-tipps-16)
  * [Kapitel 17 - Prüf- und Messergebnisse auswerten und dokumentieren](#kapitel-17---pr-f--und-messergebnisse-auswerten-und-dokumentieren)
    + [Management-Tipps](#management-tipps-17)
  * [Kapitel 18 - Optimierungsmöglichkeiten ermitteln](#kapitel-18---optimierungsm-glichkeiten-ermitteln)
    + [Management-Tipps](#management-tipps-18)
  * [Kapitel 19 - Verbesserungsmassnahmen planen und umsetzen, Sicherheitskultur fördern](#kapitel-19---verbesserungsmassnahmen-planen-und-umsetzen--sicherheitskultur-f-rdern)
    + [Management-Tipps](#management-tipps-19)
  * [Kapitel 20 - Strategie, Konzepte, Notfallpläne, ISMS und Massnahmen anpassen](#kapitel-20---strategie--konzepte--notfallpl-ne--isms-und-massnahmen-anpassen)
    + [Management-Tipps](#management-tipps-20)
  * [Kapitel 21 - Kontinuierliche Qualitätsverbesserung](#kapitel-21---kontinuierliche-qualit-tsverbesserung)
    + [Management-Tipps](#management-tipps-21)
- [Fragen](#fragen)



Die Studierenden erhalten einen vertieften Einblick in das Manage- ment von Informationssicherheit und lernen die grundlegenden Konzepte und Prozesse, um in einer Firma die Informationssicher- heit aufzubauen, zu überwachen, zu prüfen und laufend zu verbes- sern.

Spezifische Methoden der Informationssicherheit, wie Methodik zur Erstellung von Sicherheitskonzepten, Security Incident Manage- ment können die Studierenden verstehen und aufbauen.

Die Studierenden können Frameworks, Standards und Prozesse (Abläufe) verstehen, interpretieren, anwenden, entwerfen, hinterfra- gen und verbessern.


---

## Lerninhalte

### Aufbau eines ISMS (Information Security Management System)
- Phasen einer typischen Cyberattacke
- Vorgehen zum Aufbau eines Informationssicherheitsmanagementsystems (ISMS) 
- IT Sicherheitsstrategie
- Repetition und Vertiefung Risikoanalyse
- Aufbauorganisation für ein ISMS
- Personelle Massnahmen

### Control Frameworks & IT Security Massnahmen
- Frameworks BSI, COBIT, CIS, ISF, NIST & ITIL
- ISO Standards der ISO 2700x Familie
- Erkennen und bewerten von Sicherheitsrisiken
- Schutzbedarf und angemessene Massnahmen bestimmen

### Prozesse und Incident Management
- Prozessdesign
- Analyse und Darstellung von Verantwortlichkeiten (RACI) 
- Incident-, Problem- und Change Management
- Besonderheiten Security Incident Response
- Ausgewählte Kontrollen: IAM und Patch Management

### Nachhaltiger Betrieb und Verbesserung
- IT Security Monitoring
- Risk- & Exception Management
- Maturity Model CMMI zur Reifegradmessung
- Continuous Improvement mittels Metriken, Key Performance Indicators (KPI) sowie den Plan- Do-Check-Act (PDCA) Zyklus

### Business Continuity, Audit & Recht
- Revision (Audit)
- Fehler-Ursachen-Analyse oder Root Cause Analysis
- Schweizerische Gesetzesnormen mit Einfluss auf IT Sicherheit 
- IT Forensik
- Notfallvorsorge oder Business Continuity Management (BCM)

---
# 1 Aufbau eines ISMS (Information Security Management System)

## Lernziele

Ich kenne mögliche Vorgehensweisen um ein ISMS einzuführen.

Ich kenne die Methodik des klassischen Risikomanagements und kann diese interpretieren und wo nötig kritisch hinterfragen.

Ich kann begründen, welche organisatorischen, infrastrukturellen und technischen Massnahmen nötig sind, um ein erfolgreiches ISMS einführen und nachhaltig betreiben zu können.

Ich verstehe die Wichtigkeit des menschlichen Faktors in der Informationssicherheit und weiss, welche personellen Massnahmen die Sicherheit des Unternehmens steigern können.

## Vorbereitung

https://moodle.ffhs.ch/mod/assign/view.php?id=3731180

Lesen sie im Lehrbuch (Annino U,Romagna A., IT Security Management) die Kapitel 

2.2 - 2.4 

### CobIT - Control Objectives for Information and Related Technology

https://de.wikipedia.org/wiki/COBIT

(COSO, ISO/IEC 27001, ITIL)

Drei Dimensionen von CobIT:

- Geschäftliche Anforderungen,
- IT-Prozesse
- IT-Ressourcen

Domänen der IT-Prozesse:
- Planung und Organisation
- Beschaffung und Implementation
- Auslieferung und Unterstützung
- Überwachung und Optimierung

CobIT - Gliederung der Anforderungen

|Bereich|Anforderungen|Quellen(Beispiele)|
|---|---|---|
|Qualität|Anforderung aud dem Business|Geschäftsprozesse, Standards und Best Practices aus dem Qualitätsmanagement|
|Compilance|Normative Anforderungen|Gesetze, Regulative und branchenspezifische Vorgaben (z.B. Anforderungen der Finanzmarktaufsicht FINMA für Banken)|
|Sicherheit|Anforderungen an die IT-Sicherheit|Geschäftsprozesse, IT-Management|

CobIT – Gruppierung Kathegorien
- Menschen: Mitarbeitenden, Kunden, Lieferanten
- Anwendungen: Applikationen, Dienste (Services)
- Infrastuktur: Logistik, Gebäude, IT-Infrastuktur
- Informstionen: Datenbestände

CobIT Würfel

![](img/2021-01-29_21-58-49.png)


### ISO/IEC 27001

Anforderungen an ein systematisches IT-Sicherheitsmanagementsystem (ISMS)

https://www.iso.org/isoiec-27001-information-security.html

https://de.wikipedia.org/wiki/ISO/IEC_27001

### ITIL - Information Technology Infrastructure Library

Standard für das Servicemanagement in der Informatik

https://de.wikipedia.org/wiki/ITIL

https://wiki.de.it-processmaps.com/index.php/ITIL-Prozesse

### BSI - Bundesamt für Sicherheit in der Informationstechnik (Deutschland)

https://de.wikipedia.org/wiki/BSI-Gesetz

![](img/2021-01-29_22-19-26.png)

Strukturanalyse / Schutzbedarfsanalyse
Für die Erstellung eines Sicherheitskonzepts und insbesondere für die Anwendung der IT-Grund- schutz-Kataloge ist es erforderlich, das Zusammenspiel der Geschäftsprozesse, der Anwendungen und der vorliegenden Informationstechnik zu analysieren und zu dokumentieren. Aufgrund der heute üblichen starken Vernetzung von IT-Systemen bietet sich ein Netztopologieplan als Ausgangsbasis für die weitere technische Analyse an. Die folgenden Aspekte müssen berücksichtigt werden:
- im Informationsverbund betriebene Anwendungen und die dadurch gestützten Geschäftsprozesse,
- die organisatorischen und personellen Rahmenbedingungen für den Informationsverbund,
- im Informationsverbund eingesetzte vernetzte und nicht-vernetzte IT-Systeme,
- die Kommunikationsverbindungen zwischen den IT-Systemen und nach außen,
- die vorhandene Infrastruktur.
Die einzelnen Schritte der Strukturanalyse werden im Detail in Kapitel 4.2 dieses Dokuments in Form
einer Handlungsanweisung beschrieben.


Schutzbedarfsfeststellung
Zweck der Schutzbedarfsfeststellung ist es, zu ermitteln, welcher Schutz für die Geschäftsprozesse, die dabei verarbeiteten Informationen und die eingesetzte Informationstechnik ausreichend und angemessen ist. Hierzu werden für jede Anwendung und die verarbeiteten Informationen die zu erwartenden Schäden betrachtet, die bei einer Beeinträchtigung von Vertraulichkeit, Integrität oder Verfügbarkeit entstehen können. Wichtig ist es dabei auch, die möglichen Folgeschäden realistisch einzuschätzen. Bewährt hat sich eine Einteilung in die drei Schutzbedarfskategorien "normal", "hoch" und "sehr hoch".
Die einzelnen Schritte der Schutzbedarfsfeststellung werden im Detail in Kapitel 4.3 dieses Doku- ments erläutert.
Auswahl und Anpassung von Maßnahmen
Voraussetzung für die Anwendung der IT-Grundschutz-Kataloge auf einen Informationsverbund sind detaillierte Unterlagen über seine Struktur und den Schutzbedarf der darin enthaltenen Zielobjekte. Diese Informationen sollten über die zuvor beschriebenen Arbeitsschritte ermittelt werden. Um geeignete Sicherheitsmaßnahmen für den vorliegenden Informationsverbund identifizieren zu können, müssen anschließend die Bausteine der IT-Grundschutz-Kataloge auf die Zielobjekte und Teilbereiche abgebildet werden.
Dieser Vorgang der Modellierung wird in Kapitel 4.4 detailliert beschrieben.


Basis-Sicherheitscheck
Der Basis-Sicherheitscheck ist ein Organisationsinstrument, welches einen schnellen Überblick über das vorhandene Sicherheitsniveau bietet. Mit Hilfe von Interviews wird der Status quo eines beste- henden (nach IT-Grundschutz modellierten) Informationsverbunds in Bezug auf den Umsetzungsgrad von Sicherheitsmaßnahmen des IT-Grundschutzes ermittelt. Als Ergebnis liegt ein Katalog vor, in dem für jede relevante Maßnahme der Umsetzungsstatus "entbehrlich", "ja", "teilweise" oder "nein" erfasst ist. Durch die Identifizierung von noch nicht oder nur teilweise umgesetzten Maßnahmen werden Verbesserungsmöglichkeiten für die Sicherheit der betrachteten Geschäftsprozesse und der Informationstechnik aufgezeigt.
Kapitel 4.5 beschreibt einen Aktionsplan für die Durchführung eines Basis-Sicherheitschecks. Dabei wird sowohl den organisatorischen Aspekten als auch den fachlichen Anforderungen bei der Projekt- durchführung Rechnung getragen.


Weiterführende Sicherheitsmaßnahmen (Dringende Sicherheitsmassnahmen umsetzen)
Die Standard-Sicherheitsmaßnahmen nach IT-Grundschutz bieten im Normalfall einen angemessenen und ausreichenden Schutz. Bei hohem oder sehr hohem Schutzbedarf kann es jedoch sinnvoll sein, zu prüfen, ob zusätzlich oder ersatzweise höherwertige Sicherheitsmaßnahmen erforderlich sind. Dies gilt auch, wenn besondere Einsatzbedingungen vorliegen oder wenn Komponenten verwendet werden, die nicht mit den existierenden Bausteinen der IT-Grundschutz-Kataloge abgebildet werden können. Hierzu ist zunächst im Rahmen einer ergänzenden Sicherheitsanalyse zu entscheiden, ob für die jeweils betroffenen Bereiche eine Risikoanalyse durchgeführt werden muss.
Eine Methode für Risikoanalysen ist die im BSI-Standard 100-3 "Risikoanalyse auf der Basis von IT- Grundschutz" beschriebene Vorgehensweise. In Kapitel 4.6 wird diese Methode überblicksartig dargestellt. Die erfolgreiche Durchführung einer Risikoanalyse hängt entscheidend von den Fach- kenntnissen des Projektteams ab. Daher ist es häufig sinnvoll, fachkundiges externes Personal hinzu- zuziehen.


### Common Criteria

### OSSTMM

### FIPS 140

### Verwendung mehrerer Standards

### Weitere Regelwerke

- Basel II
- Solvency II
- Sarbanes-Oxley (SOx)
- COSO

3.2 & 3.3 

### Sicherheitsanforderungen
- Externe und interne Anspruchsgruppen
- Externe Sicherheitsanforderungen

### Anforderungsklatalog
- Grundlage für die Beurteilung von Risiken und angestrebtes Sicherheitsninveau

### IT-Sicherheitsbeauftragter
- Für die Wahrnehmung aller Belange der IT-SIcherheit ihherhalb des Unternehmens zuständig
- Funktion, Aufgaben, Kompetenzen variieren von Unternehmen zu Unternehmen
- Kontroll und Überwachungsaufgaben
- Planung und Umsetzung der notwendigen SIcherheitsmassnahmen
- Beratung der Geschäftsleitung in Sachen Sicherheitsanforderungen und Unterstützung bei Umsetzung

#### ISMS - Informationssicherheits-Managementsystem
- IT-Sicherheitsforum zum Auf- und Ausbau der IT-Sicherheit

### Datenschutzbeauftragter
- Wenn Unternehmung untner das DGS fällt

### Notfallteam
- Einberufung bei bestimmtem Eintreten von Ereignissen

### Risikomanagement

### IKS - Internes Kontrollsystem

4.2 & 4.3 

### PDCA-Zyklus - Plan, Do, Check, Act

### Risikoanalyse
- ermitteln und bewerten

#### Vorbereitung
- initiieren
- ab- und eingrenzung des Untersuchungsbereich

#### Durchführung
- identifizieren und bewerten

### Risikoidentifikation
- Risikomatrix
- Abschätzen von Gesamtrisiko und Abhängigkeiten

### Risikobbewertung
- Beurteilung der identifizierten Risiken
- quantitative
    - Bewertung des Schadensausmass anhand absoluter Bewertung der Auswirkungen in CHF 
- qualitative Bemessung
    - Bewertung des Schadensausmass anhand einer relativen Zuordnung

#### Risk Map
- Schnelle Übersicht des Ausmass und Eintrittswahrscheinlichkeit
- Netzdiagramm
- Blasendiagramm

### Business-Impact-Analyse
- Grundlage der unternehmerischen Sicherheitsstrategie
- Betriebliche Notfallvorsorge
- Untersuch des Ausfalls von einzeknen Geschäftsprozessen
- Ausfallszenarien durchspielen
- Schutzziele
    - Vertraulichkeit
    - Verfügbarkeit
    - Integrität
    - Verbindlichkeit
    
### BCM - Business Continuity Managements

### Strukturanalyse
- Erhebung der IT-Inftrastruktur
- Grundlage für Ermittlung des Schutzbedarfs nach BSI
-Vorgehen
    - Netzplan erheben
    - Komplexität durch clustering reduzieren
    - Schutzbedarf von Anwendungen festlegen
    - Schutzbedarf von Komponenten festlegen
    - Schutzbedarf für Kommunikationsverbindungen festlegen
    - Schutzbedarf für Räume festlegen
    - Ergebnisse interpretieren

5 

### Sicherheitsstrategie und Sicherheitskonzept

#### Unternehmensstrategie
- mittel- und langfristige ausrichtung des Unternehmens
- Erfolgschance erhalten / ausbauen
- Misserfolgschancen vermeiden / reduzieren

#### Intelligente IT-Strategie
- Sie trägt zum Wachstum bei, indem sie neue Märkte oder Geschäftsfelder erschliesst
- Sie trägt zum Wachstum bei, indem sie neue Märkte oder Geschäftsprozesse ermöglicht
- Sie trägt zur Effektivitätssteigerung bei, indem sie wichtige Beiträge zur Zielerreichung liefert
- Sie trägt zur Effizienzsteigerung bei, indem sie die Geschäftsprozesse unterstützt und optimeirt

#### IT-Sicherheitsstrategie
- interne und externe Sicherheitsanforderungen erfüllen, ohne Nachteile für das Unternehmen
- Aussagen zu wesentlichen Schutzzielen, regelt grob die verbundenen Verantwortlichkeiten
- Aussagen zur Risikobewältigungsstrategie
- Ist Leitfaden und Legitimationsgrundlage für Sicherheitsaktivitäten

#### IT-Sicherheitskonzept
- Wie werden Vogaben der IT-Strategie umgesetzt
- Welche Risiken mit welchen Massnahmen bekämpfen
- Werkzeug der IT-Sicherheitsbeauftragten zur Erfüllung der Sicherheitsanforderungen
- Angepasst an Realität und laufend optimiert
- Vor der Erstellung des IT-Sicherheitskonzept
    - Bewertung der Risiken von bestehenden oder geplanten Geschäftsprozessen und Applikationen verbunden sind
    - Festlegung der RIsikobewältigungsstrategie
    - Auswahl angemessener Sicherheitsmassnahmen
    
#### Kontrollmodell
- Prozessbezogene Steuerungsvorgaben (Control Objectives)

7 

### Managementsystem für IT-Sicherheit entwickeln

#### Komponenten eines ISMS
- Managementprinzipien
- Ressourcen
- Mitarbeitende
- Sicherheitsprozesse

#### MAnagementprinzipien
- Gesamtverantwortung übernehmen
- IT-Sicherheit integrieren
- Aktive beteiligung der Führungspersonen
- Verständliche und realistische Ziele
- GLeichgewicht zwischen AUfwand und Nutzen
- Vorbildfunktion

### Kontrolle der Überwachungsziele

### Auswertung von Sicherheitsvorfälle
- Entscheidungsfähigkeit
- Reaktinsfähigkeit
- Handlungsfähigkeit
- Schadenminimierung
- Effektivität

### Überwachunngs und Detektionssysteme

### Beweissicherung

### Eskalationsplan

10

### Personelle Massnahmen

#### Personelle SIcherheitsmassnahmen

#### Sicherheitsweisungen
- Unterschreiben bei Eintritt
- Vertreterregelungen
- Non-Disclosure-Agreement

#### Regelmässige Sicherheitsschulungen
- Unwissenheit und Fahrlässigkeit vermindern
- Präventions- und Reaktionsmassnahmen
- Zentrale Anlaufstelle für Meldungen
- Disziplinarische Massnahmen

#### Austritt von Mitarbeitenden
- Berechtigungen ändern oder sperren
- Daten, Dokumente, Geräte, Schlüssel, Zugangskarten, usw. zurückgeben

11

### Organisatorische Massnahmen

#### Konzepte für die IT-Sicherheit
- Virenschutz
- Wireless-Communication
- Dateiablage
- Zutritts-, Zugangs-, Zugriffsberechtigung
- Logging
- Standard Arbeitsplatz
- Peer-to-Peer Konzept
- Dokumentationskonzept
- Schlüsselverwaltungskopnzept
- Systemmanagement

#### Weisungen
- Passwortgebrauch
- Umgang mit Betriebsmittel
- Ungesicherte Netzzugänge
- Datenaustausch
- Wartungs- und Reparaturarbeiten
- Verantwortlichkeiten, Aufgaben, Funktionen
- Einrichten von Benutzern, Benutzergruppen und Rechten
- Gebäudereinigung

#### Verwaltung der Konzepte, Weisungen, Sicherheitsdokumente
- Dokumentenmanagementsysteme
- Intranet
- Wiki

#### Life-Cycle-Management
- Einhaltung der Sicherheitsanforderungen
- Beschaffung und Entwicklung
- Betrieb und Wartung
- Entsorgung von Systemkomponenten

#### Management-Tipps
- Planung organisatorischer Sicherheitsmassnahmen
- Grundlage ist das ISMS und Life-Cycle-Management
- Sicherheitskonzepte und -weisungen
- Dokumentationssystem


## Präsenz

Programm Präsenzveranstaltung 1

Dauer	Thema
10'	Begrüssung und Agenda
10'	Fragen zur Vorbereitung
15' Phasen einer typischen Cyberattacke
30' Vorgehen zum Aufbau eines ISMS
30' IT Sicherheitsstrategie
15'	Pause
30'	Repetition, Festlegen der Arbeitsgruppen und Übung
20'	Aufbauorganisation für ein ISMS
20'	Personelle Massnahmen
15'	Didaktischer Puffer

######Lernziele
- Ich kenne mögliche Vorgehensweisen um ein ISMS einzuführen
- Ich kenne die Methodik des klassischen Risikomanagements und kann diese interpretieren und wo nötig kritisch hinterfragen 
- Ich kann begründen, welche organisatorischen, infrastrukturellen und technischen Massnahmen nötig sind, um ein erfolgreiches ISMS einführen und nachhaltig betreiben zu können 
- Ich verstehe die Wichtigkeit des menschlichen Faktors in der Informationssicherheit und weiss, welche personellen Massnahmen die Sicherheit des Unternehmens steigern können

#### Agenda
- Phasen einer typischen Cyberattacke
- Vorgehen zum Aufbau eines ISMS
- IT Sicherheitsstrategie 
- Repetition und Vertiefung Risikoanalyse
- Aufbauorganisation für ein ISMS
- Personelle Massnahmen

![](img/2021-01-30_09-53-28.png)

#### Bedrohungen wandeln sich
Technologie entwickelt sich in nie gekannter Geschwindigkeit:
- Wenig Zeit für Individuen, Gesellschaft und Industrie, sich an neue Gegebenheiten anzupassen

Mehr Leistung zu tieferen Preisen:
- Transistoren sind um Faktor 90k effizienter und Faktor 60k günstiger als 1971
- Know-how (z.B. Hacking) lässt sich in Software bündeln und Amateuren zur Verfügung stellen (Script Kiddies)

![](img/2021-01-30_10-00-13.png)

Neue Technologie hat im Laufe der Geschichte die Kriegsführung verändert:
- Piken beendeten die Dominanz der Kavallerie auf dem Schlachtfeld
- Kanonen überwanden unbesiegbare Festungen

Da erfolgreiche Verbrecher oft ‘early adopters’ sind, spielt dieser Mechanismus auch zwischen Gesetz und Kriminellen:
- Die Bonnot Bande in Frankreich (1912) verwendete Repetiergewehre und Automobile, während die Polizei sie auf Fahrrädern und Pferden verfolgte
- Das Darknet hat Kryptowährungen schnell und umfassend angenommen

#### …sind aber auch inhärent
Why would cyber security be any more difficult than most technological problems?
- Most technology-related efforts are concerned with ensuring that something good happens. **Security is all about ensuring that bad things never happen.**
- In security, not only do you have to find “bugs” that make the system behave differently than expected, you have to **identify any features of the system that are susceptible to misuse and abuse**, even if your systems behave exactly as you expect them to.
- If security is all about ensuring that bad things never happen, that means **we have to know what those bad things are**.

#### Enemy Within…
Ex-Mitarbeiter hackt sich in Firma.

#### …and Outside
![](img/2021-01-30_10-07-29.png)

|Attacker|-->|Objectives|Resources|Proceeding|
|---|---|---|---|---|
|Nation, States, Agencies|-->|- Information - Fighting Crime/Terrorism - Espionage - Sabotage| | |
|Terrorists|-->| | | |
|(Organized) Crime|-->| | | |
|Hacktivists, Groups|-->| | | |
|Vandals, Script Kiddies|-->| | | |

APT - Advanced persistent Thread

https://de.wikipedia.org/wiki/Advanced_Persistent_Threat

Zero Day - Exploits

https://de.wikipedia.org/wiki/Exploit

#### Data Breaches
![](img/2021-01-30_10-13-12.png)

http://www.informationisbeautiful.net/visualizations/worlds-biggest-data-breaches-hacks/

![](img/2021-01-30_10-15-50.png)

### Phasen einer Cyberattacke
- Adversary
- Researche -> Xing, LinkedIn
- Infiltration -> Eine Maschine infizieren, Priviledge Escalation
- Discovery -> Was ist spannend 
- Capture -> Was ist wo
- Exfiltration -> Güter aus der Firma entfernen
- Marketplace -> Güter verkaufen

#### Marktplatz
How much is your stolen data worth on the dark web?
- Credit and debit cards: $5 to $45 n Bank login credentials for a $2,200 balance bank account: $190
- Bank login credentials plus stealth funds transfers to US banks: $500 for a $6,000 account balance, $1,200 for a $20,000 account balance
- Login credentials for online payment services such as PayPal: between $20 and $50 for account balances from $400 to $1,000; between $200 and $300 for balances from $5,000 to $8,000
- Login credentials for online premium content services such as Netflix: as little as $0.55


Exploits: 

https://zerodium.com/program.html


### Vorgehen zum Aufbau eines ISMS

#### ISIS12
- Es gibt verschiedene Frameworks die beschreiben, wie ein ISMS aufgebaut werden kann. Wir werden zwei behandeln: BSI & COBIT.
- Die Frameworks geben gute Hilfestellung dabei, was aufgebaut werden soll. Wieviel davon und in welcher Tiefe Sie das in Ihrer Umgebung umsetzen bleibt Ihnen überlassen. 
- Aufbauend auf dem BSI Standard hat der Bayrische Sicherheitscluster e.V. das ISIS12 Vorgehensmodell (Informations-SIcherheitsmanagementSystem in 12 Schritten) erstellt. Es ist zugeschnitten auf die Bedürfnisse des Mittelstands und beschreibt ein einfach einzuführendes ISMS, welches ISMS und IT-Service Management verknüpft. Das Verfahren kann als mögliche Vorstufe zur ISO/IEC 27001- bzw. BSI IT-Grundschutz-Zertifizierung verwendet werden. 
  
https://www.it-sicherheit-bayern.de/produkte-dienstleistungen/isis12

##### Übersicht
- Unser Kurs folgt grob dem ISIS12 Ansatz:

![](img/2021-01-30_10-33-49.png)

##### Phase 0: Wieso benötige ich ein ISMS?
- Ist das Management auf ihrer seite und comittet?

##### Phase 1: Initialisierung
- Leitlinie erstellen
    - Das zentrale Strategiepapier welches Informationssicherheitsziele, sowie die daraus abgeleiteten und abzuleitenden Konzepte und Massnahmen festhält
- Mitarbeiter sensibilisieren
    - Auf allen Organisationsebenen muss die Notwendigkeit von IT Security kommuniziert werden.
    - Wir gehen hier etwas weiter als ISIS12 und beleuchten ausserdem Sicherheitsüberprüfung (vetting) von Mitarbeitern, Schulung und Austritt von Mitarbeitern (IAM)
    
Gibt es einen Weg die Sicherheit zu umgehen - Sie wird umgangen...

##### Phase 2: Aufbau- & Ablauforganisation
- Informationssicherheits-Team aufbauen
    - Aufbau, die Zusammensetzung, die Aufgaben und Pflichten des Informationssicherheitsteams
- IT Dokumentationsstruktur festlegen
    - Definition einer zielführenden und aktuellen IT-Dokumentation. Neben IT Security Policy, technischen Standards und relevanten Prozessen gehört auch die CMDB (Configuration Management Database) zu diesem Schritt.
- IT Servicemanagement-Prozess einführen
    - ISIS12 konzentriert sich auf die ITIL Teilprozesse Change Management, Incident Management und Problem Management.
    - Wir werden diesem Vorschlag folgen (ITIL wird in einem eigenen Kurs umfassend behandelt), schauen uns aber zusätzlich auch an, wie diese Teilprozesse im ITIL Framework positioniert sind.

Wichtig!: CMDB - Configuration Management Database: Inventar

https://de.wikipedia.org/wiki/Configuration_Management_Database

##### Phase 3: Entwicklung und Umsetzung
- Kritische Applikationen identifizieren
    - Anhand von Schutzbedarf für Vertraulichkeit, Integrität und Verfügbarkeit (Confidentiality, Integrity, Availability) werden unternehmenskritische Anwendungen identifiziert und bewertet. Aus der Bewertung ergeben sich die Maximal Tolerierbare Ausfallzeit (MTA) und die Service Level Agreements (SLA)
    - Die Themen Risikomanagement und Business Continuity Planning (BCM) machen uns mit den für diesen Schritt notwendigen Werkzeugen vertraut.
- IT-Struktur analysieren
    - Definition des Informationsverbunds: Erfassung der technischen, personellen, organisatorischen und infrastrukturellen Objekte, die für die Verarbeitung von Informationen im Unternehmen benötigt werden.
    - Dieses Thema ist sehr firmenspezifisch und wird uns daher nur kurz im BCM Teil beschäftigen.
- Sicherheitsmassnahmen modellieren
    - Zuordnung der empfohlenen Sicherheitsmassnahmen zu den unternehmenskritischen Objekten. Stichwort: Control Frameworks
    - Im Rahmen der Präsenz 2 werden wir verschiedene Control Frameworks kennenlernen und dieses Thema mit den COBIT und BSI Frameworks vertieft behandeln.
- Ist-Soll vergleichen, Umsetzung planen, Umsetzen
    - Diese drei Schritte sind firmenspezifisch und ausserdem eher Projektmanagement als IT Security.
- Revision
    - Prüfung der erfolgreichen Umsetzung des ISMS.
    - ISIS12 hat hier einen Projekt Ansatz: wir werden sehr viel weiter gehen und untersuchen, wie Sicherheit nachhaltig erbracht und kontrolliert werden kann.

>Wichtig!: BCM - Business Continuity Planning
>
>https://de.wikipedia.org/wiki/Betriebliches_Kontinuit%C3%A4tsmanagement
>
> - Was man nicht kennt, kann man nicht managen: ohne ein vollständiges, akkurates Inventar sind weder die Assets noch ihre aktuelle Konfiguration bekannt.

##### IAM 
ToDo
Prinzip:

Joiner

Mover

Leavers

### IT Sicherheitsstrategie

#### Definition
Unter Strategie werden in der Wirtschaft klassisch die (meist langfristig) geplanten Verhaltensweisen der Unternehmen zur Erreichung ihrer Ziele verstanden. In diesem Sinne zeigt die Unternehmensstrategie in der Unternehmensführung, **auf welche Art ein mittelfristiges (ca. 2–4 Jahre) oder langfristiges (ca. 4–8 Jahre) Unternehmensziel erreicht werden soll**. Diese klassische Definition von Strategie wird heute vor allem auf Grund ihrer Annahme der Planbarkeit kritisiert. Eine homogene Auffassung von Strategie herrscht in der wissenschaftlichen Literatur nicht vor.

http://de.wikipedia.org/wiki/Strategie_(Wirtschaft)

#### Strategiebaum
![](img/2021-01-30_10-43-19.png)

##### So viel wie nötig… …so wenig wie möglich

- Absolute Sicherheit ist nicht (wirtschaftlich) erreichbar.
- Security bringt immer Einschränkungen mit sich: Kosten, Funktionalität, Bedienungsfreundlichkeit, …
- Information Security (Strategie, Risikomanagement, ISMS, …) ist daher, zwischen ‘zu viel’ und ‘zu wenig’ die heute optimale Balance zu erreichen.

![](img/2021-01-30_10-55-48.png)

#### SWOT Analyse - Strengths, Weaknesses, Opportunities und Threats

**Nur wer weiss, was er nicht will, kann sich auf das konzentrieren, was er erreichen möchte**

Die SWOT-Analyse (Strengths, Weaknesses, Opportunities und Threats) ist ein Instrument der Strategischen Planung - sie dient der Positionsbestimmung und der Strategieentwicklung.
- SWOT-Analysen beschreiben Zustände, Strategien hingegen Aktionen.
- Bei der SWOT-Analyse wird keine Priorisierung vorgenommen. Es lassen sich keine konkreten Massnahmen ableiten, Massnahmen werden also weder beschlossen noch umgesetzt.

![](img/2021-01-30_11-02-45.png)

##### Umsetzung
![](img/2021-01-30_11-44-40.png)

Relevanz:

Alles ist Relevant und von grosser Bedeutung

Reife:

Vieles ist gut angedacht, fast alles ist nicht fertig gedacht worden und nucht fertig gemacht worden

#### Kritik an Strategischer Planung
- 95% der Manager geben an, dass strategische Planung wichtig ist – sie wird aber nur von der Hälfte tatsächlich eingesetzt. Nur 8% geben an, dass in ihrem Unternehmen eine eindeutige Strategie vorliegt.
- Der Zusammenhang zwischen strategischer Planung und Unternehmenserfolg lässt sich nur vermuten.
- Eine von zwei Strategieimplementierungen scheitert.
- In der Strategieliteratur wurde der Einstieg von Honda um das Jahr 1960 in den amerikanischen Markt für Motorräder als Ergebnis professioneller Strategischer Planung dargestellt. Die verantwortlichen Manager dazu: "In Wirklichkeit bestand unsere ganze Strategie darin, einfach nachzusehen, ob wir in den Vereinigten Staaten überhaupt irgendetwas verkaufen können." Eine Planung lag überhaupt nicht vor.

### Risikoanalyse & Wahrnehmung von Risiken

#### Definition
- Die Risikoanalyse (threat and risk assessment) findet in allen Lebensbereichen Anwendung und stellt damit ein wichtiges Mittel zur Bewertung bestimmter Situationen, Vorhaben, Ereignisse oder Systeme dar.
- Risikoanalyse ist in der Betriebswirtschaftslehre die Abschätzung der Kosten möglicherweise eintretender Risiken zwecks Risikomanagement und Ermittlung der Höhe kalkulatorischer Wagniskosten.
- Risikoanalysen werden allgemein zur Identifikation und Bewertung von Risiken eingesetzt, damit im Rahmen des Risikomanagements mögliche negative Ereignisse mit Präventionsmassnahmen vermieden, reduziert oder auf Dritte abgewälzt werden können. Des Weiteren werden sie für die Kommunikation von Risikosituationen verwendet, um z. B. die Risikowahrnehmung zu fördern.

>Wichtig zum Thema Risiko:
>- Welche zwei Dinge benötigen wir für Risikoabschätzung:
>  - Eintrittswahrscheinlichkeit
>  - Schadensausmass

>Wichtig zum Thema Security:
>- Grundsätze:
>  - IT-Sicherheit ist kein Selbstzweck, sondern dient immer einem übergeordneten Ziel (Unterstützung eines Geschäftsprozesses ider Wahrung der Privatsphäre).
>  - Es gibt keine 100% Sicherheit, aber es gibt eine für ein Problem abgemessene SIcherheti. Diese muss für jedes Projekt / jede Anwendung / jede Firma individuell bestimmt werden.
>  - Sicherheit soll einfach sein und soll den Benutzer möglichst nicht behindern.
>  - Sicherheit ist eine Kette und nur so stark wie ihr schwächstes Glied.
>    
>- Confidentiality (Vertraulichkeit)
>    - Vertraulichkeit bedeutet: Daten vor unbefugtem Zugriff zu schützen.
>        - Need to know Prinzip
>        - Zugriffsberechtigungen
>        - Datenverschlüsselung (Kryptographie)
>        - Daten verstecken (Steganographie)
>        
>- Integrity (Integrität)
>    - Integrität besagt, dass Daten über einen bestimmten Zeitraum vollständig und unverändert sein müssen.
>        - Dazu müssen die Daten vor Verlust und nicht autorisierter Veränderung geschützt werden.
>        - Integrität kann mit kryptographisch gesichterten Prüfsummen geprüft/bewiesen werden (Hash).
>        
>- Availability (Verfügbarkeit)
>    - Die Verfügbarkeit stellt sicher, dass ein berechtigter Benutzer zu dem Zeitpunkt auf eine Information zugreifen kann, zu der er sie braucht.
>    - Eine Verfügbarkeit von 99.99% entspricht dabei einer jährichen Ausfallzeit von ca. 1h.
    
#### Wahrnehmung von Risiken

- Welches Tier ist gefährlicher?

|Hai|Bambi|
|---|---|

Wahrnehmung… …kann täuschen

Average number of fatalities per year per animal (USA):
- Deer (vehicular collisions) 130 
- Dogs 18 
- Snakes 15 
- Sharks 0.4

![](img/2021-01-30_11-43-58.png)

#### Spezialfall: Cyber
- Wir nehmen an, sicher zu sein, da alle Systeme funktionieren 
    - Aber: Besitz impliziert nicht Kontrolle 
        - Illusion von Kontrolle 
        - Kumulation von Risiken
- Menschen reagieren erst nach einem offensichtlichen Incident; typische (schlechte) Verhaltensmuster sind:
    - Überreaktionen (Stichwort: ‘Security Theater’) 
    - Schutz gegen bereits eingetretene, oft einmalige Bedrohungen (‘Movie-Plot Security’)
- Awareness für abstrakte Risiken zu schaffen, ist schwierig

#### Risikoanalyse Schematischer Ablauf
![](img/2021-01-30_12-02-26.png)

#### Risikobewertung
- Risiko = Eintretenswahrscheinlichkeit x Schadensausmass 
- In der Regel nimmt man für beide Werte die schwersten Ausprägungen an 
- Die Werte lassen sich oft nicht berechnen, sondern müssen aufgrund von Annahmen bestimmt werden
- Visualisierung erlaubt, das Risiko in Relation zum Risk Appetite zu setzen:

![](img/2021-01-30_12-06-54.png)

- Mögliche Strategien im Umgang mit Risiken:
- Eliminieren: Die Eintretenswahrscheinlichkeit auf Null senken.
- Überwälzen: Das Risiko versichern, bzw. auf einen anderen Marktteilnehmer übertragen. 
- Reduzieren (Mitigieren): Das Schadensausmass reduzieren.
- Akzeptieren: Das Risiko als geschäftsnotwendig akzeptieren, laufend überwachen und regelmässig neu bewerten.

#### Identifizieren von Risiken
Bottom-up
- Ausgehend von schützenswerten Assets mögliche Bedrohungen identifizieren und die daraus entstehenden Risiken bewerten 
    - Zielgerichtet 
    - Möglicherweise lückenhafter Schutz

Top-down
- Ausgehend von einem risikobewerteten Katalog von Bedrohungen (Threat Model) bestimmen, welche Assets betroffen sind 
    - Tendenziell umfassender 
    - Höherer Initialaufwand

#### Threat Model

- Bedrohungsmodell wählen (OCTAVE Tables 6 & 7, ISF, …) 
- Use cases sammeln und in Modell einfügen 
- Instanzen bestimmen 
- Risk rating bestimmen 
- Abdeckung bestimmen 

![](img/2021-01-30_12-11-16.png)

Dokumentierte Bedrohungslage:

![](img/2021-01-30_12-11-31.png)

>Definition der "OK" Positionen sind selbst definierte quantitative oder qualitative Aspekte.
>
>- quantitativ: ab 90% Antivirus Programme auf allen Endgeräten gilt als i.O.
>
>- qualitativ: alle Endgeräte mit dem Programm Antivir123 gelten als i.O.

### Aufbauorganisation ISMS

#### Übersicht
Ein ISMS aufzubauen bedingt Aktivitäten in verschiedenen Bereichen und Disziplinen. Viele dieser Aktivitäten laufen parallel, die untenstehende Reihenfolge ist daher nur ein Vorschlag, wie die Themen angegangen werden können.

1. Managementprinzipien aufstellen

2. Sicherheitsstrategie erstellen

3. IT Security Organisation definieren und implementieren

4. Ressourcen bereitstellen

5. IT Security Policy erstellen und kommunizieren

6. Sicherheitskonzept(e) erstellen

7. Prozesse, Richtlinien, Weisungen erstellen

8. Nachhaltigen Betrieb sicherstellen

#### Managementprinzipien
- Gesamtverantwortung übernehmen: Gilt nicht nur für Management und TopManagement, end-to-end accountability muss auf allen Ebenen verstanden und gelebt werden
- IT Security integrieren: Sicherheit nachträglich einzubauen ist teuer und nicht immer erfolgreich
- Aktive Beteiligung und Vorbildsfunktion des Managements: ohne konstante und konsequente Umsetzung durch Management kann Security nicht erreicht oder gehalten werden
- Ziele müssen SMART sein (Specific, Measurable, Assignable, Realistic, Time-related)
- Gleichgewicht zwischen Aufwand und Nutzen: z.B. durch Anwendung des Pareto-Prinzips (80% Ertrag durch 20% Aufwand)

#### Organisation
Obwohl IT Security Aufgabe der gesamten Organisation ist sollten die unten aufgeführten Rollen formell zugeteilt sein:
- Geschäftsleitung 
- Information Security Officer: Gesamtverantwortung für Security im Auftrag der Geschäftsleitung; zentrale Stelle "There's no 'T' in Information Security": es geht nicht nur um Technologie 
- Risk Manager: Identifikation und Verwaltung von Risiken; zentral oder verteilt, evtl. in Personalunion mit Information Security Officer 
- Dateneigentümer: verteilte Rolle; wer Daten erstellt klassifiziert sie 
- Prozessverantwortliche: Erstellen, implementieren, messen und korrigieren von Prozessen 
- IT Spezialisten: Verantwortlich für spezifische Sicherheitskonzepte

#### Ressourcen
Die Geschäftsleitung muss sich im Klaren darüber sein, dass Security Geld kostet und die entsprechenden Mittel nachhaltig zur Verfügung stellen. Ressourcen beinhalten mehr als auf den ersten Blick ersichtlich ist:
- Dedizierte Security Mitarbeiter (z.B. SecOf oder Risk Manager) 
- Aufwand von indirekt involvierten Mitarbeitern (Schulung, Miteinbezug in Risiko Management, Erstellen und Pflege von Sicherheitsrichtlinien, durch Security getriebener Mehraufwand in Prozessen, …)
- Security kann die Architektur von Gebäude, Netzwerk, Applikationen beeinflussen und damit Mehrkosten generieren 
- Es werden Produkte und/oder Technologien eingeführt, welche sonst nicht benötigt würden (Antivirus, Firewall, IDS, UPS, Badges, …)

#### Sicherheitskonzepte
- Zutritts- und Zugriffsberechtigungs Konzept
  - Wer darf was unter welchen Voraussetzungen
- System Management
  - Anforderungen an Administration von Systemen, Change Management
- Virenschutz 
- Dokumentationskonzept
  - Was muss dokumentiert werden (Architektur, Systemdokumentation, Prozesse, Organisation) und wo sind die Dokumente abzulegen
- Dateiablagekonzept
  - Wie werden Daten klassifiziert und welcher Schutz ist nötig
- Logging Konzept
  - Welche Logdaten werden wie und wo gespeichert 
  - (Achtung: das Lehrbuch verwendet eine zu enge Definition und spricht nur von Login-Rechten)

#### Sicherheitskonzepte: Struktur
- Sicherheitskonzepte sollten einem definierten Raster folgen, formell abgenommen und regelmässig überprüft und aktualisiert werden.
- Sie bilden die Basis für das Interne Kontrollsystem der Informatik.
- Bis zum Präsenzblock 2 haben Sie die Aufgabe, 5 der von SANS publizierten General Policy Templates zu studieren und die ihnen gemeinsame Kapitelstruktur zu ermitteln
- Wir werden Ihre Erkenntnisse im Präsenzblock 2 diskutieren
- Bei Interesse finden Sie auf Moodle ausserdem Links zu Musterrichtlinien des BSI und zu den Sicherheitsanforderungen der Bundesverwaltung (fakultative Lektüre)

#### Prozesse
Security soll nicht etwas zusätzliches, sondern eingebetteter Bestandteil der Organisation sein. Folgerichtig ist die Mehrzahl der Prozesse relevant für Security. Das zeigt sich auch in der Breite der in Block 2 behandelten Frameworks.

Einige der zentraleren Prozesse, welche mit Vorteil bereits bei der Einführung eines ISMS auf die Sicherheitspolitik des Unternehmens ausgerichtet werden:
- CMDB (Configuration Management Database) 
  - Was man nicht kennt, kann man nicht managen: ohne ein vollständiges, akkurates Inventar sind weder die Assets noch ihre aktuelle Konfiguration bekannt.
- Architektur 
  - Security muss von Beginn an Teil des Designs werden damit sie effizient und kostengünstig funktioniert. 
- Change- und Problemmanagement (Block 3) 
  - Diese Prozesse helfen, Security Incidents zu vermeiden, bzw. zu identifizieren.
- Incident Management (Block 3) 
  - Überwachen der Sicherheit und Reaktion auf Sicherheitsverstösse ist einer der Kernprozesse.
- Business Continuity Management – BCM (Block 5) 
  - Traditionell ein in Security angesiedelter Prozess: wie schützen wir uns gegen Ausfälle und wie gehen wir vor um uns von einem Ausfall zu erholen.
- Risikomanagement (Blöcke 1 & 4) 
  - Wie erkennen, dokumentieren und verwalten wir Risiken, so dass wir die Unternehmung nicht unangemessenen Risiken aussetzen.
- Measurement / Reporting (Block 4) 
  - Management will wissen, dass das in Security investierte Geld die gewünschten Ergebnisse zeigt. Dazu muss Security messbar gemacht und der Erfolg kommuniziert werden. Das ist auch Basis für die laufende Qualitätsverbesserung.
- Security 'Kernprozesse': Systemsicherheit, Patching & Benutzerverwaltung Systeme sicher zu konfigurieren, auf dem aktuellen Stand zu halten und nicht benötigte Berechtigungen zu entfernen sollte selbstverständlich sein. Dies schützt nicht gegen alle Angriffe, erhöht aber die Sicherheit signifikant.
- HR Prozesse (Block 1) 
  - Mitarbeiter und Partner stellen nicht die Mehrzahl der Angreifer aber das Schadenpotenzial ist tendenziell höher.

### ISMS & PDCA

![](img/2021-01-30_12-38-41.png)

>Plan: Wie ist es heute?
>
>Do: Wie komm ich dahin?
>
>Check: Wie weit bin ich auf dem Weg dorthin?
>
>Act: Was muss ich tun um SOLL näher zu kommen?

### Personelle Massnahmen

#### Mitarbeiter: ein Security Problem?
- Aktuell eher nicht:

![](img/2021-01-30_12-42-38.png)

https://enterprise.verizon.com/resources/reports/dbir/

- Trotzdem: Mitarbeiter und Partner sind kritische Ressourcen für eine Unternehmung und sowohl Betriebsführung als auch die internen Kontrollen hängen von ihrer Motivation, Kompetenz und Loyalität ab

#### Security Awareness
Wieviel ist noch erträglich, wieviel ist zuviel?

Zuviel Veränderung kann kontraproduktiv sein, Mitarbeiter machen nicht mehr mit.

Belohnung ist besser als Bestrafung.
- Oft sind Verstösse gegen die Sicherheit keine bewusste Entscheidung sondern schlicht die Folge von mangelndem Sicherheitsbewusstsein oder fehlender Ausbildung.
- Sicherheitsbewusstsein besteht auch auf Stufe Unternehmung.
- Das nötige Bewusstsein zu schaffen und zu erhalten ist eine delikate Aufgabe: zu viel oder zu penetrant kann kontraproduktiv sein. 
- Mögliche Massnahmen:
  - Schulung neu eintretender Mitarbeiter / Jährliche Wiederholung 
  - Regelmässige Kommunikation des Information Security Officer 
  - Kontrollen, bei denen korrektes Verhalten belohnt wird (im Gegensatz zu: 'Fehlverhalten bestraft wird') 
  - Andere Kanäle: Security Apéro, Wettbewerb, Abgabe von Antivirus Software an Mitarbeiter, …

#### Wichtige HR Prozesse
##### Rollenbeschreibung
  - Sofern es die Grösse der Unternehmung zulässt sollten Rollen mit Aufgaben, Kompetenzen und nötiger Qualifikation beschrieben werden.
##### Rekrutierung
  - Hintergrundcheck: Strafregister- und Betreibungsamtsauszug. 
  - Beruflicher Hintergrund: Echtheit von Zeugnissen und Diplome.
##### Ausbildung
  - Regelmässige und zielgerichtete Ausbildung ist nicht nur eine Investition in die Qualifikation der Mitarbeiter sondern auch motivationssteigernd.
##### Erkennen fehlender Stellvertretung
  - Welche Mitarbeiter verursachen inakzeptable Probleme falls sie ungeplant ausfallen (z.B. durch Unfall oder Krankheit).
##### Schlüsselpersonen identifizieren
  - Welche Mitarbeiter sind in Positionen, in welchen sie die Firma empfindlich schädigen könnten? (z.B. System- oder Datenbankadministratoren).
##### Verletzung von Aufgabentrennung erkennen (Segregation of Duties)
  - Um Missbrauch und Unfälle zu verhindern, müssen manche Aufgaben auf verschiedene Personen aufgetrennt werden. Beispiele dafür sind Erfassung und Freigabe von Zahlungen oder Softwareentwicklung und Systembetrieb.
##### Leistungsbeurteilung
  - Klassischer HR Prozess. Aus Sicht Security sind Leistungsabfälle von Interesse, da sie auf Probleme hinweisen können.
##### Rollenwechsel und Austritt
  - Berechtigungen sollen bei internen Wechseln oder Austritten zeitnah entfernt werden. Bei kündenden oder gekündigten Mitarbeitern kann die Gefahr von Data Leaks bestehen.

###### Nachbearbeitung

Empfehlung: ITIL-Foundations Kurs besuchen!

https://moodle.ffhs.ch/mod/assign/view.php?id=3731177

---

# 2 Control Frameworks und IT Security Massnahmen

###### Lernziele

Ich kenne gängige Industriestandard Frameworks zur Steuerung von Informatik und Informationssicherheit.

Ich kann Sicherheitsrisiken identifizieren und bewerten.

Ich kann den Schutzbedarf von Assets bestimmen.

Ich kann Informationssicherheits-Massnahmen aufzeigen und deren Einsatz anforderungsgerecht empfehlen.

## Vorbereitung

https://moodle.ffhs.ch/mod/assign/view.php?id=3731180

1

### IT-Sicherheit
Das Gefahrenpotenzial für geschäftsrelevante Daten und Informationen, die durch ICT-Systeme geseichert oder verarbeitet werden, auf ein tragbares Risikoniveau zu senken.

- IT-Infrastruktur
  - Netzwerke, Hard- und Software
  - Gebäude
  - User

### Schutzziel Datensicherheit
Die Sicherheit von Daten und Informationen während der Aufbewahrung, Bereitstellung und Verarbeitung

#### Schutzziele (CIA)

#### Vertraulichkeit (Confidentiality)
- Nur berechtigte Personen haben Zugriff

#### Integrität (Integrity)
- Vollständige und unverfälschte Daten
##### Realität
- Integre Daten und Informationen entsprchen der Realität
##### Aktualität
- Integre Daten und Informationen sind aktuell
##### Authentizität 
- Integre Daten und Informationen kommen von vertrauenswürdiger Quelle

#### Verfügbarkeit (Availability)
- Sicherstellung, dass Daten und Anwendungen jederzeit zur Verfügung stehen

#### Verbindlichkeit
- Daten sind verpflichtend und rechtsgültig
##### Authentizität
- Absender und Empfänger sind echt
##### Rechtsgültigkeit
- Gesetzliche und vertragliche Bedingungen werden eingehalten
##### Nicht-Abstreitbarkeit
- Nachvollziehbarkeit der Daten und Iformationen

### Schutzziel Datenschutz
- Zielt auf den Schutz der Daten und Informationen vor Missbrauch, unberechtigter Einsichtnahme, Verwendung, Änderung oder Verfälschung ab

Wichtige Schutzziele: 
- Vertraulichkeit
- Integrität

### Datensicherung
Umfasst alle technischen und organisatorischen Vorsorgemassnahmen, die sicherstellen, dass die Ziele der Datensicherheit erreicht werden. Verhinderung, dass Schutzziele verletzt werden.

### Notfallvorsorge (Continuity Management, Contingency Management)
Umfasst alle personellen, technischen und organisatorischen Vorsorgemassnahmen, die bei Stötungen zum Tragen kommen, die die Schutzziele beeinträchtigen. Massnahmen die nach einer Verletzung der Schutzziele umgesettzt werden müssen.

### Sicherheitsgefahren und -bedürfnisse
Gefahren erkennen und eigenes Sicherheitsbedürfnis klären

#### Bedrohung, Verletzbarkeit und Risiko

##### Bedrohungen

|Kathegorie|Kurzbeschreibung|Beispiele|
|---|---|---|
|Höhere Gewalt|Können nicht beeinflusst werden. z.b. Umwelteinflüsse|Wasser, Feuer, Hagel, usw.|
|Organisatorische Mängel|Fehlerhafter Ablauf und Aufbau einer Organisation. Verlaufen eng mit Menschlichem Fehlverhalten|Mangelhafte Kontrolle, Fehlende Kompetenzen Unklare Zuständigkeiten|
|Menschliche Fehlhandlungen|Nicht vorsätzlich durch Unwissenheit, Unachtsamkeit oder Überforderung als Ursache|Irtümliche Erfassung falscher Daten, Unbewusste Aktivierung einer Malware, Installation inkompatibler Systemkomponenten|
|Vorsätzliche Handlungen|Vorsätzlich herbeigeführt|Zerstörung einer Netzverbindung, Diebstahl eines Datenträgers, DoS-Attacke auf einen Server|
|Technisches Versagen|Technisch bedingte Störung eines Systems oder einzelner Komponente|Hardwaredefekt, Softwarefehler, Netzwerkunterbruch|

##### Verletzbarkeit
Ein bestimmter Mangel z.B. Sicherheitslücke in einem bestimmten Objekt

##### Risiko
Eine Bedrohung die auf eine bestimmte Verletzbarkeit trifft und einen gewissen Schaden verursachen kann

#### Sicherheitsbedarf und Risikobereitschaft

##### Güterabwägung

|Fragen|Aspekte|
|---|---|
|Wovon leben wir heute?|Welche Produkte verkaufen wir?, Welche Dienstleistungen verkaufen wir?|
|Wovon wollen wir morgen leben?|Produkte entwickeln und verkaufen|
|Welche Prozesse haben direkt mit den Produkten und Dienstleistungen zu tun?|Managementprozess, Kernprozess, Untersttützungsprozess|
|Wo erbringen wir diese Prozesse?|Geografisches Umfeld, Politisches Umfeld, Soziales Umfeld|
|Wie erbringen wir diese Prozesse?|Organisastionsform, Fertigungs- Produktionsmethode, Technische Hilfsmittel|
|Welche Unternehmensstrategie verfolgen wir?|Marktauftritt, Expansionssttratiegie, Firmenpolitik|

#### Sicherheitsmassnahmen
Oftmals teuer und beeintträchtigen Geschäftsprozesse
- Sicherheitsmassnahmen hangen an jeweiligen Risiken und müssen für jeden Geschäftsbereich separat betrachtet werden

#### Sicherheit der Geschäftsprozesse
Sicherheitsmassnahmen erhöhen i.d.R. die Komplexität und verringern die Durchlaufgeschwindigkeit eines Geschäftsprozesses
- Vermeidung von unnötigen Schnittstellen (Schwachsttellen vermeiden)

#### Rolle der Informatik
Governance-Prinzip: Beherrschbarkeit, Steuerung und Überwachung einer Organisation

- Enterprise Governance: Gesamtes Unternehmen
- Corporate Governance: Unternehmensprozesse, Risikomanagement, Informations- und Offenlegunspflicht
- IT-Governance: Informationsbearbeitung und -verarbeitung

#### Sicherheitskriterien

#####Technische Sicherheitskriterien:

|Abkürzung|Standard bzw. Kriterienkatalog|Kurzbeschreibung des Inhalts|
|---|---|---|
|TCSEC|Trusted Computer Evaluation Criteria|Standard der US-Regierung für die Bewertung und Zertifizierung der Sicherheit von Computersystemen|
|ITSEC|Information Technology Security Evaluation Criteria|Europäischer Standard für die Bewertung und Zertifizierung der Sicherheit von Computersystemen|
|CTCPEC|Canadian Trusted Computer Product Evaluattion Criteria|Internationaler Standard für die Bewertung und Zertifizierung der Sicherheit von Computersystemen|
|CC|Common Criteria|Standard der US-Regierung für die Bewertung und Zertifizierung der Sicherheit von Computersystemen|

##### Organisatorische udn personelle Sicherheitskriterien

|Abkürzung|Standard bzw. Best Practices|Kurzbeschreibung des Inhalts|
|---|---|---|
|CobIT|Control Objectives for Information and Related Technology|Kontrollfragen zu IT-Prozessen, u.a. bezüglich Effizienz und Effektivität, sowie umfassendes Management der Prozesse|
|ITIL|IT Infrastructure Library|Best-Practice-Sammlung von IT-Prozessen|

3.1

### Anforderungen an die Sicherheit

#### Externe Anforderungen
- Gesetze
- Branchenverbände
- Kunden
- Lifersnten

#### Interne Anforderungen
- Weisungen und Richtlinien

#### Sicherheitsanforderungen ermitteln

1. Fach- oder Geschäftsbereiche mit potentiellen Sicherheitsanforderungen identifizieren
2. Externe und Interne Sicherheitsanforderugnen durch die betroffenen Fach-/Geschäftsbereiche erheben lassen
3. Übergreiffende Anforderungen an die IT-Sicherheit gemeinsam mit den Verantwortlichen aller betroffenen Fach-/Geschäftsbereiche festhalten

#### Anfoderungskatalog
Mithilfe eines Anfoderungskataloges können die erhobenen Anforderungen schriftlich festgehalten werden und später zur Beurteilung der Risiken des angestrebten Sicherheitsniveaus herangezigen werden.

4.4

### Strukturanalyse und Schutzbedarfsstetllung

#### Netzplan erstellen
Grafische Übersicht mit allen Komponenten der IT-Infrastruktur.

- Client- und Server-Computer, Netzkomponenten, Netzdrucker etc.
- Netzverbindungen zwischen diesen Komponenten
- Verbindungen des betrachteten Bereichs nach aussen

Netzplan muss die nötigen Ressourcen zugewiesen bekommen um ihn aktuell halten zu können.

#### Komplexität durch Gruppenbildung reduzieren
Komponenten aus Netzplan verdichten. Gleichartige Komponenten werden zu einer Gruppe zusammengefasst.

#### Infrastrukturkomponeten erheben
Gruppierte Komponenten auflisten und beschreiben. Beinhaltet vernetzte Systemkomponente und Datenträger oder mobile Arbeitsplätze.

#### Geschäftskritische Anwendungen erfassen
Folgende Kriterien kommen zum Zug:
- Anwendungen die hoch verfügbar sein müssen
- Anwendungen mit Dagenbeständen, deren Integrität unbedingt sichergestellt werden muss
- Anwendungen miit Datenbeständen, deren Vertraulichkeit sichergestellt werden muss

#### Systemkomponeten pro Anwendung erheben
Erhebung der zugehörigen Systemkomponenten gemäss Anwendung. Zur Bestimmung des Schutzbedarfes werden alle Komponenten die für den Betrieb einer Anwendung mit hohem Schutzbedarf bbenötigt sind, ebenfalls mitt hohem Schutzbedarf behandelt.

#### Schutzbedarf für Anwendungen festlegen
Mit der Frage: "Was wäre, wenn...?" können später anhand der Begründungen, Sicherheitsmassnahmen legitimiert werden.

#### Schutzbedarf für Systemkomponenten festlegen
Komponenten haben grundsätzlich den selben Schutzbedarf wie zugehörige Anwendungen

#### Schutzbedarf für Kommunikationsverbindungen feststellen
Verbindungen sollten den Schutzbedarf der verwendeten Anwendung entspechen.

- Welche Kommunikationsverbindungen stellen Aussenverbindungen dar? (Verbindungen in fremde Systeme)
- Welche Kommunikationsverbindungen laufen über fremden Grund?
- Welche Kommnikastionsverbindungen übernehmen Daten bzw. Informationen mit hohem Schutzbedarf?
- Welche Kommunikationsverbindungen sind für das Unternehmen bzw. für Geschäftsprozesse von zentraler Bedeutung?

Informationen erfassen pro Verbindung:
- Verbindungsstrecke
- Innen-/Aussenverbindung
- Begründung des Schutzbedarfes

#### Schutzbedarf für Räume festlegen
Zonenkonzept für Zutrittsberechtigungen festlegen.

6

### Risiken analysieren, Schutzbedarf feststellen, Schwachsttellen aufdecken

8

9

12



## Präsenz

### Aufgabe 'Policy Templates'

#### SANS Policies: Kapitelstruktur

Policy Struktur 
- Hilft um nichts zu vergessen
- Wann soll das Dokument das nächste mal überarbeitet werden?

|Überschrift|Inhalt|
|---|---|
|Overview|Übersicht / Zusammenfassung: Was darf der Leser in dieser Policy erwarten. Das ‘Management Summary’.|
|Purpose|Ziel des Dokuments: Warum besteht diese Policy, was will sie regeln oder verhindern?|
|Scope|Wen betrifft diese Policy? Üblicherweise werden das Organisationseinheiten, Benutzer(gruppen) oder Technologien sein.|
|Policy|Der Kern des Dokuments. Hier sind die Policy Requirements (‘Anforderungen’) beschrieben. Umfang und Detaillierungsgrad der Beschreibung hängt von der Komplexität des Themas und Existenz von Standards ab. Eine Clean Desk Policy kann komplett in einer Policy beschrieben werden, aber um zu definieren wie ein Computer sicher aufgesetzt und betrieben wird benötigt es ausserdem Standards um die Details zu regeln.|
|Policy Compliance|Dieses Kapitel enthält 3 Unterkapitel: • Policy Measurement: Wie wird Einhaltung, bzw. Abweichung von der Policy gemessen? • Exceptions: Sind Ausnahmen erlaubt und wenn ja, wie sind sie zu beantragen, genehmigen, dokumentieren und revalidieren? • Non-Compliance: Welche Konsequenzen hat die Nicht-Einhaltung dieser Policy?|
|Related Documents|Sofern und soweit andere ‘Standards, Policies and Processes’ mit dieser Policy in Verbindung stehen wird dies hier aufgeführt. Eine Policy über sicheren Serverbetrieb wird voraussichtlich auf verschiedene Standards verweisen: Setup, Change Management, Backup, …|
|Definitions and Terms|Falls und soweit Fachbegriffe oder Abkürzungen verwendet werden, sind sie hier aufgeführt und erklärt.|
|Revision History|Darf in keinem offiziellen Dokument fehlen: welche Versionsnummer hat das Dokument, wann wurde es veröffentlicht, wer ist der Eigentümer. Optional können hier auch weitere Aspekte aufgeführt werden wie: wer hat die Policy genehmigt oder wann ist die nächste Überarbeitung geplant.|

#### Frameworks: Übersicht

##### Treiber
- Die behandelten IT Governance Frameworks zielen nicht ausschliesslich auf Definition und Erhaltung von Sicherheit sondern sind aus der Notwendigkeit entstanden, die IT so zu steuern, dass sie zu vertretbaren Kosten nachhaltig Mehrwert für die Unternehmung generiert
- Dazu fokussieren die Frameworks im Wesentlichen auf folgende Bereiche:
  - Schaffen von Unternehmenswert
    - IT muss die Ziele der Unternehmung aktiv unterstützen und ermöglichen Abstimmung zwischen Business und IT ist entscheidend
  - Minimieren von IT Risiken Schutz der Assets und Fortführung der Unternehmensprozesse im Krisenfall
  
##### Übersicht gebräuchlicher Frameworks
- Es bestehen eine respektable Anzahl von Frameworks, die zum Aufbau eines internen Kontrollsystems, bzw. zur Definition/Bestimmung von anwendbaren Kontrollen verwendet werden können:


- BSI – Bundesamt für Sicherheit in der Informationstechnik 
- COBIT – Control Objectives for Information and Related Technology
- CIS – Center for Internet Security
- NIST – National Institute of Standards and Technology
- ISO 27002 - International Organization for Standardization
- ISF – Information Security Forum

##### Center for Internet Security
- Das Center for Internet Security (CIS) ist ein Zusammenschluss von Organisationen und Einzelpersonen, um Materialien und Ressourcen zum Thema Internet-Sicherheit zur Verfügung zu stellen. Die Verwaltung der 2000 gegründeten Organisation befindet sich in East Greenbush, New York.
- CIS in Version 7.1 listet zu 20 Kontrollen ca. 170 Subkontrollen.
  
Hauptpunkt für die Verwendung von CIS:
- Weiters stehen zu allen gebräuchlichen Plattformen umfangreiche Benchmarks (Wegleitungen zur sicheren Konfiguration) zur Verfügung
- Mindestanforderungen für Compliance Tools vorhanden

- Das Material kann bei https://www.cisecurity.org/ kostenlos bezogen werden; die Kontrollen (v7.1) sind im IT General Controls Spreadsheet zu diesem Kurs enthalten

##### National Institute of Standards and Technology
- Das NIST ist eine Bundesbehörde der Vereinigten Staaten. Von 1901 bis 1988 hiess es National Bureau of Standards (NBS). Das Institut hatte im Jahr 2016 ein Budget von 964 Millionen US-Dollar zur Verfügung.
- Das NIST ist für Standardisierungsprozesse zuständig. Bekannte Standards sind z.B. DES, AES sowie die Hashfunktionen der SHA-Familie.
- Die im NIST Cybersecurity Framework (CSF) in Identify – Protect – Detect Response – Recover ist inzwischen Quasi-Standard.
- Die ca. 100 Kontrollen CSF Core sind weniger bekannt, aber eine weitere gute Quelle für Kontrollen.


- Auch NIST ist kostenlos (www.nist.gov) und der CSF Core ist im IT General Controls Spreadsheet enthalten.

![](img/2021-02-27_09-59-55.png)

Amerikanisches Gegenstück zum BSI

##### International Organization for Standardization
- ISO ist seit 1947 ein Verein nach schweizerischem Recht mit Sitz in Genf, der internationale Normen erarbeitet.
- Es gibt eine Vielzahl von ISO Normen, aus Sicht IT Security sind die 2700x interessant:
  - ISO/IEC 27001 Informationssicherheits-Managementsysteme
  - ISO/IEC 27002 Leitfaden für das Informationssicherheits-Management
  - ISO/IEC 27032 Richtlinien für die Cybersicherheit
- Die ISO Standards sind nicht frei verfügbar und daher nicht im IT General Controls Spreadsheet zu diesem Kurs enthalten

Die verschiedenen Phasen sollten bekannt sein:

![](img/2021-02-27_10-09-04.png)

Verein mit Sitz in Genf

Problem: Kostenpflichtig

##### Information Security Forum
- ISF ist seit 1989 eine non-profit Organisation in England.
- ISF bietet den (zahlenden) Mitgliedern zugriff auf:
  - Tools und Methoden (z.B. The Standard of Good Practice for Information Security)
  - Forschung und Reports
  - Wissensaustausch
- ISF Material ist nicht frei verfügbar und daher nicht im IT General Controls Spreadsheet zu diesem Kurs enthalten
- https://www.securityforum.org/

#### BSI

https://www.bsi.bund.de

https://www.bsi.bund.de/DE/Themen/Unternehmen-und-Organisationen/Standards-und-Zertifizierung/IT-Grundschutz/IT-Grundschutz-Kompendium/it-grundschutz-kompendium_node.html

##### BSI: Organisation
- Das Bundesamt für Sicherheit in der Informationstechnik (BSI) in Bonn ist eine deutsche Bundesbehörde, die für Fragen der IT Sicherheit zuständig ist
- Gegründet 1991
- 600 Mitarbeiter (2014)
- Erstellung und Pflege der IT Grundschutz Kataloge
- Regelmässige Veröffentlichungen zum Thema IT Sicherheit (z.B. Studien und Richtlinien)

##### BSI: IT Grundschutz Kataloge
- Sammlung von Dokumenten (mehr als 4'440 Seiten) zur Erkennung und Bekämpfung sicherheitsrelevanter Schwachstellen
- Aufbau:
  - Bausteinkatalog
  - Gefährdungskataloge 
  - Massnahmenkataloge 
  - Weiterführendes Material Checklisten, Formulare, Muster und Beispiele
  - Software 
    - GSTOOL, eingestellt Ende 2014 Verschiedene Tools auf Basis des IT Grundschutz von anderen Herstellern sind noch erhältlich (z.B. Verinice)

![](img/2021-02-27_10-26-11.png)

https://www.bsi.bund.de/DE/Themen/ITGrundschutz/ITGrundschutzKompendium/bausteine/bausteine_node.html

##### BSI: Vernetzung der Kataloge
- Bausteine sind Gefahren ausgesetzt, denen mit Massnahmen begegnet wird
- Massnahmen oder Gefährdungen können auch für andere Bausteine relevant sein
- Das führt zur Vernetzung der Komponenten und erhöht die Komplexität

![](img/2021-02-27_10-26-52.png)

##### BSI: Bausteine
- B1 Übergreifende Aspekte
  - Organisation, Management, Personal, Konzepte, Incident Management, Patch Management, Outsourcing, Requirements Management
- B2 Infrastruktur
  - Bauliche Aspekte (von RZ bis Heimarbeitsplatz)
- B3 IT-Systeme
  - Clients, Server, Virtualisierung, Netzwerkinfrastruktur, Telefonanlagen, Fax, Mobile Devices
- B4 Netze
  - Netzwerke, VPN, WLAN, VoIP
- B5 Anwendungen
  - Datenträger, (Datenbanken, Webserver,) AD, DNS

Zu jedem Baustein werden typische Gefahren und Massnahmen aufgezeigt

![](img/2021-02-27_10-36-38.png)

##### BSI: Gefährdungskataloge
- G0 Elementare Gefährdungen
  - Diebstahl, Missbrauch, Manipulation, Zerstörung, Fehlfunktion, …
- G1 Höhere Gewalt
  - Feuer, Wasser, technische Katastrophen im Umfeld, Ausfall eines Gebäudes, …
- G2 Organisatorische Mängel
  - Gefährdungen, welche durch fehlende oder unzureichende Prozesse entstehen
- G3 Menschliche Fehlhandlungen
  - Fehlerhafte, unbeabsichtigte, unzulässige oder fahrlässige Handlungen
- G4 Technisches Versagen
  - Ausfälle, Überlastungen, Soft- oder Hardwarefehler
- G5 Vorsätzliche Handlungen
  - Missbrauch, Abhören, Malware, Manipulation, Maskerade, …
  

Gefärdungen müssen nicht zwingend IT bezogen sein - in der InfoSec werden spezifische Gefährungskataloge eingesetzt.

##### BSI: Massnahmenkataloge
- Aufbau der einzelnen Massnahmen:
  - Verantwortliche für die Initiierung und die Umsetzung 
  - Beschreibung der Massnahme 
  - Kontrollfragen zur korrekten Umsetzung
    - Wie sie "grün" aus?
    - Wann wurde das Ziel erreicht?

- M1 Infrastruktur 
- M2 Organisation 
- M3 Personal 
- M4 Hardware und Software 
- M5 Kommunikation 
- M6 Notfallvorsorge

#### COBIT

##### COBIT: Organisation
- Control Objectives for Information and Related Technology:
  - Veröffentlicht von Information Systems Audit and Control Association, ISACA 
  - Ursprünglich Werkzeug für IT Revision, heute ein Framework für Governance und Einhaltung von Compliance (gesetzliche Anforderungen) 
  - Versionen: COBIT 1 (1996), COBIT 4.1 (2007), COBIT 5.0 (2012), COBIT 2019 (2019)
- Wir verwenden die (veraltete) Version 4.1 da diese im Gegensatz zu 5.0 frei erhältlich und verwendbar ist (http://www.isaca.org/Knowledge-Center/cobit/Pages/Overview.aspx)

- COBIT Mission:
  - To research, develop, publicise and promote an authoritative, up-to-date, internationally accepted IT governance control framework for adoption by enterprises and day-to-day use by business managers, IT professionals and assurance professionals

##### COBIT: Geschichte

![](img/2021-02-27_10-49-22.png)

##### COBIT: Top-Down Vorgehen
- Ausgehend von Unternehmenszielen werden IT-Ziele festgelegt, welche die Architektur der IT beeinflussen
- Angemessen definierte und betriebene IT-Prozesse (34 in COBIT 4.1) gewährleisten die Verarbeitung von Informationen, die Verwaltung von ITRessourcen (Personal, Technologie, Daten, Anwendungen) und die Erbringung von Services
- Auf Ebene Unternehmen, IT, Prozess und Aktivität sind Mess- und Zielgrössen zur Beurteilung der Ergebnisse und der Performance festgelegt
- Die Messung der Zielerreichung erfolgt Bottom-Up und ergibt so einen Steuerungs-Zyklus

![](img/2021-02-27_10-49-44.png)

##### COBIT: Gesamtsicht

![](img/2021-02-27_10-50-15.png)

##### COBIT: Prozesse

![](img/2021-02-27_10-50-35.png)

##### COBIT: Prozessbeschreibung
- Process Description
  - Kurze Beschreibung 
  - Prozessziel (High-Level Control Objective) 
  - Wesentliche Aktivitäten 
  - Wesentliche Messgrössen


- Control Objectives
  - Total 210
  

- Management Guidelines
  - Input und Output des Prozesses 
  - Aufgaben- und Zuständigkeitsmatrix (RACI-Matrix)
  - Ziele und Metriken zur Beurteilung des Prozesses und zur Beurteilung des Beitrags einzelner Aktivitäten zu den Zielen des Prozesses und den Beitrag des Prozesses wiederum zu den Zielen der IT


- Maturity Model
  - Reifegradmodell, das – angelehnt an CMM die jeweiligen typischen Ausprägungen des Prozesses in sechs Reifegradstufen (0 bis 5) beschreibt


##### COBIT 5: Vergleich zu Version 4
- Statt 34 Prozessen sprechen wir nun von 37 Controls und 210 Management Practices
- Die Controls sind ähnlich wie in v4 beschrieben, bestehender Content wurde aber neu geordnet und erweitert (z.B. klarere Aussagen zur den Maturitäts-levels) und neu werden z.B. auch Policies oder Unternehmenskultur aufgeführt.

![](img/2021-02-27_11-01-02.png)

Die neueste Version COBIT 2019 führt zusätzlich Design Factors ein:

![](img/2021-02-27_11-00-32.png)

#### ISO 27001
- Die International Organization for Standardization (ISO) hat über 20 Standards in der sogenannten ISO 27000-Familie (auch: ISO27k)
- ISO 27001 ist der Standrad, welcher Anforderungen an ein ISMS beschreibt
- Er ist entstanden aus dem British Standrard 7799 und wurde 2005 erstmals veröffentlicht
- ISO selbst führt keine Zertifizierungen durch womit die folgenden drei Möglichkeiten bestehen, die Konformität zu zeigen:
  - Konformität von sich aus verkünden
  - Konformität von Kunden bestätigen lassen
  - Verifikation der Konformität durch einen unabhängigen externen Auditor

### ITIL

Empfehlung: ITIL Foundation Kurs

#### ITIL: Organisation
- Die IT Infrastructure Library (ITIL) wird seit 1989 vom Cabinet Office in London entwickelt
- ITIL beschreibt in fünf Kernbänden Komponenten und Abläufe des Lebenszyklus von IT-Services
- Damit ist ITIL nicht direkt mit den bereits vorgestellten ISMS vergleichbar aber eine wertvolle Ergänzung um serviceorientierte, industrialisierte IT erbringen zu können

#### ITIL: Bücher und Inhaltsübersicht
- Servicestrategie (Service Strategy)
  - Konzeptioneller und strategischer Hintergrund von IT-Dienstleistungen 
  - Strategie, Service Portfolio, Financial- und Demand Management
- Serviceentwicklung (Service Design)
  - Architektonische Rahmenbedingungen, Übertragung der Geschäftsperspektive in Services 
  - Service Katalog, Governance, Security, Availability-, Capacity- und Continuity Management, SLA
- Serviceinbetriebnahme (Service Transition)
  - Umsetzung der geschäftlichen Anforderungen in konkrete IT-Dienstleistungen 
  - Change-, Release-, Asset- und Configuration Management
- Servicebetrieb (Service Operation)
  - Vereinbarte Leistung im täglichen Betrieb störungsfrei aufrechterhalten und sichern 
  - Service Desk, Event- und Problem Management, Access Management
- Kontinuierliche Serviceverbesserung (Continuous Service Improvement)
  - Nachhaltige Aufrechterhaltung und Optimierung der Servicequalität 
  - Service Reporting, Service und Management Information Reviews, Kommunikationsplan, Kundenzufriedenheit, ROI

#### ITIL: Wallchart

![](img/2021-02-27_11-06-41.png)

### Frameworks anwenden: Risiken erkennen & Schutzbedarf bestimmen

#### Preventive & Detective Controls

Kontrollen werde grob in zwei Kategorien unterteilt: 
- Preventive Control (Vorgelagerte Kontrolle)
  - Eine Kontrolle, welche verhindert, dass ein Ereignis eintritt
- Detective Control (Nachgelagerte Kontrolle)
  - Eine Kontrolle, welche erkennt, dass ein Ereignis eingetreten ist

|Preventive|Detective|
|---|---|
|Abgeschlossene Türen|Einbruchsalarm|
|4-Augen Prinzip bei Buchungen|Kontrolle der ausgehenden Zahlungen|
|Firewall|Intrusion Detection System|
|ISMS|Internal Audit|
|Access Control|Logs|

- Preventive Controls sind vorzuziehen, aber nicht immer möglich

#### Gruppenarbeit
Vorgehen:
- Gefahren erkennen
- Massnahmen auswählen die die meisten Gefahren gleichzeitig bekämpfen
- Katalog zusammenstellen für den individuellen Gebrauch


- BSI
  - Spezifischere Massnahmen 
  - Eine Massnahme von zweifelhaftem Nutzen für die vorliegende Frage (M 5.46)
- COBIT
  - Umfassender, aber auch allgemeiner: weniger Hilfestellung zu spezifischen Fragen (z.B. war IDS keine der identifizierten Massnahmen)


- Trotzdem: beide Ergebnisse sind als Ausgangspunkt gut verwendbar

###### Nachbearbeitung

https://moodle.ffhs.ch/mod/assign/view.php?id=3731186

https://moodle.ffhs.ch/mod/quiz/view.php?id=3731187

---

# 3 Prozesse und Security Incident Management

###### Lernziele

Ich kann Prozesse und RACIs erstellen, beurteilen und Schwachstellen erkennen.

Ich kenne die Unterschiede und das Zusammenspiel zwischen Incident-, Problem- und Security Incident Management.

Ich weiss wie sicherheitsrelevante Vorfälle entdeckt und gehandhabt werden können.

Ich kann die Besonderheiten der Security Incident Response im Vergleich zum Incident Management Prozess aus ITIL erklären

Ich kann ausgewählte Kontrollen beschreiben und umsetzen.

## Vorbereitung



## Präsenz

Dauer	Thema
10'	Fragen zur Vorbereitung
20'	Präsentation der Gruppenarbeit  (Gruppe B)
15' Prozessdesign
30'	Analyse und Darstellung von Verantwortlichkeiten (RACI)
30' Incident-, Problem- und Change Management
15' Pause
30'	Security Incident Response
30'	Diskussion ausgewählter Kontrollen: IAM und Patch Management 
15'	Didaktischer Puffer

### Agenda

- Diskussion der Aufgaben 
- Prozessdesign
- Analyse und Darstellung von Verantwortlichkeiten (RACI); Diskussion der RACI Aufgabe aus der Vorbereitung auf die Präsenz
- Incident-, Problem- und Change Management
- Security Incident Response

![](img/2021-03-24_21-41-49.png)

### Business Case

#### Business Case - Details

- Investitionen sollten grundsätzlich nur getätigt werden, wenn der zu erwartende Nutzen die aufzuwendenden Kosten übersteigt 
- Bei grösseren Investitionen (z.B. Einführung eines ISMS) kann es sich lohnen, diese Analyse strukturiert und dokumentiert anzugehen 
- Der Business Case ist eine Möglichkeit die Ergebnisse einer solchen Analyse dem Management zur Entscheidung vorzulegen

#### Business Case - Kapitelübersicht

|Kapitel|Inhalt, Bemerkungen|
|---|---|
|Management Summary|Kurze Beschreibung des Inhalts in zwei bis drei Absätzen für den eiligen Leser.|
|Überblick (Thematik und Zielsetzung)|Weshalb dieser Business Case, was wird grob angestrebt?|
|Definition und Abgrenzung|Was ist in scope dieses Business Cases und – noch wichtiger – was ist nicht in scope.|
|Kostenpositionen|Aufgeteilt nach einmalig und wiederkehrend sind hier die Kosten des Business Cases aufgeführt. Eines der zentralen Kapitel: hier steht, um was wir das Management anfragen. Die Aufstellung muss komplett, akkurat und ehrlich sein – soweit das zu diesem Zeitpunkt möglich ist. Hier die Zahlen zu schönen kann später zu schmerzhaften Diskussionen führen…|
|Monetäre Vorteile|Aufstellung einmaliger und wiederkehrender Kostenersparnis. Soweit nicht-monetäre Aspekte berechenbar sind sollten sie hier aufgeführt werden (z.B. Einsparung von Arbeitszeit).|
|Nicht-monetäre Aspekte|Nicht alle Treiber für ein Projekt sind finanzieller Natur. Nicht, oder nur schwer bezifferbare Vorteile und Gründe werden hier aufgeführt. Beispiele sind: Treiber von Aussen (Gesetze) oder Risikomanagement (Unternehmensrisiko, Projektrisiko, finanzielle Risiken)|
|Bewertung|Kurze Erklärung, weshalb dieser Business Case bewilligt werden sollte. Falls Varianten zur Auswahl stehen enthält dieses Kapitel unsere Empfehlung und die Erklärung, weshalb diese Variante und nicht die anderen.|
|Entscheidungsvorlage|Das formelle Gesuch an die Geschäftsleitung, das vorgestellte Projekt anzugehen.|

### Prozessdesign

#### Definition 'Prozess'

- Zielgerichtete logische Abfolge von:

**Eingang, Verarbeiten, Ausgang & integrierte Regelkreise**

![](img/2021-03-24_21-53-10.png)

Der Output eines Prozesses muss für den (internen oder externen) Kunden von Nutzen sein

#### Prozess Design: Erste Schritte

- Identifikation von:
  - Input: Wie (durch wen) wird der Prozess gestartet, was wird zur Durchführung benötigt? 
  - Output: Was ist das gewünschte Ergebnis?
  - Suppliers: Wer muss beitragen, damit das Ergebnis erreicht werden kann?
  - Customer: Wer ist der Kunde, bzw. Nutzniesser des Ergebnisses?
- Welche Schritte werden benötigt, um das Ziel zu erreichen?
- In welcher Reihenfolge müssen sie durchlaufen werden?
- Wer führt diese Schritte durch, was ist jeweils Input, was Output?

Auf Basis dieser Informationen kann ein erstes Prozessdiagramm erstellt werden

#### Prozessdiagramm: Erstellung

- In einem ersten Schritt dient das Prozessdiagramm dazu, ein gemeinsames Verständnis des Prozesses bei allen beteiligten Parteien zu erreichen.
- Basierend darauf werden dann:
  - Fehlende oder überflüssige Schritte korrigiert 
  - Probleme im Prozess eliminiert 
  - Schnittstellen zwischen Abteilungen definiert 
  - Schlüsselkontrollen definiert 
  - Verantwortlichkeiten beschrieben 
  - Prozessdokumentationen erstellt
- Diese Schritte werden iterativ durchlaufen bis alle Stakeholder überzeugt sind, einen ihren Anforderungen genügenden, effizienten und effektiven Prozess definiert zu haben.

#### Prozessdiagramm: Visualisierung

- Methoden zur Visualisierung:
  - Flowchart 
  - Swimlane 
    - Vertikal (siehe rechts) 
    - horizontal (nächste Folie)
- Flowchart ist einfacher und in IT aus der Programmierung oft schon bekannt
- Swimlane benutzt weitgehend die aus Flowchart bekannten Symbole, bildet zusätzlich aber auch die ausführende Organisation ab und ist daher meist aussagekräftiger

Lesen Sie dazu:

http://de.wikipedia.org/wiki/Business_Process_Model_and_Notation

![](img/2021-03-24_21-55-23.png)

![](img/2021-03-24_21-56-07.png)

#### Kontrollen

- Kontrollen stellen sicher, dass ein Prozesses wie geplant durchgeführt wird und dass die Ergebnisse von gleichbleibender Qualität sind.
- Konzentration auf Schlüsselkontrollen erlaubt 'so viel wie nötig, so wenig wie möglich‘.
- Eine Key Control:
  - darf nicht versagen, da sonst das Ergebnis des Prozesses nicht oder nur in nicht adäquater Qualität erbracht wird 
  - verhindert oder entdeckt grobe Fehler 
  - wird nicht durch eine weitere Kontrolle kompensiert, d.h. wenn sie versagt ist es unwahrscheinlich, dass dies (bzw. der entstandene Fehler) entdeckt wird 
  - muss gemessen und rapportiert werden

> 85% of errors are built into the process. 
> Only 15% are caused by the people working in the process.
>
> W. Edwards Deming

#### Prozessdesign: Praxis

![](img/2021-03-24_22-02-33.png)

#### Prozessdesign: Abschluss

- Ein Prozess ist erfolgreich eingeführt, wenn:
  - Kundenzufriedenheit gegeben ist 
  - das Prozessdiagramm mit allen Parteien verifiziert und vereinbart ('agreed') ist 
  - Schlüsselkontrollen und KPI identifiziert sowie gemessen sind 
  - RACI erstellt, verifiziert und vereinbart ist 
  - detaillierte Prozessbeschreibungen erstellt und verfügbar sind 
  - regelmässiges Reporting gegen KPI stattfindet 
  - Management Massnahmen ergreift, falls KPI verfehlt werden 
  - der Prozess Teil des QA und Verbesserungsprozesses ist 
  - der Prozess regelmässig überprüft ('revalidiert') und gegebenenfalls angepasst wird

(Vergleichen Sie dazu auch CMMI in der nächsten Präsenz)

#### Prozessdesign: Subjektivität

- Oft gibt es keinen perfekt korrekten Prozess: wie in der Programmierung können Ziele meist auf unterschiedlichen Wegen erreicht werden
- Die Key Controls und ihre Gewichtung bestimmen zu einem grossen Teil wie ein effizienter Prozess aussieht
- Unterschiedliche Personen definieren Prozesse unterschiedlich: Durch Diskussion der verschiedenen Standpunkte wird die optimale Lösung identifiziert und im Prozess implementiert
- Einige formelle Kriterien:
  - Ein Prozess darf nie in einen undefinierten Zustand kommen (‘Error Handling’) 
  - Es gibt immer (mindestens) einen Start und der Prozess muss zu einem Endpunkt kommen

#### Gruppenarbeit: Prozessanalyse

- Das Prozessdiagramm beschreibt einen generischen Security Incident Management Prozess:
  - Incidents werden von einer Level 1 Organisation angenommen und bearbeitet oder an eine Level 2 Organisation weitergeleitet 
  - Schwerwiegende Incidents werden, falls vom Management so entschieden, als Major Incidents behandelt
- Leider haben sich verschiedene formelle und logische Fehler eingeschlichen
  

- Bilden Sie Gruppen und:
  - Identifizieren Sie die Key Controls 
  - Finden Sie die Fehler im Prozessdiagramm
- Zeit: 30 Minuten, dann Besprechung im Plenum

![](img/2021-03-24_22-05-48.png)

(Lösung)

![](img/2021-03-24_22-06-05.png)

(Key Controls)

![](img/2021-03-24_22-06-26.png)

False Positive?

Wenn eine flasche Entscheidung getroffen wird und dies unter dem Radar ohne Ticket durchgewunken wird.
- Benötigt es ein 4 Augen-Prinzip? -> Meist zu teuer...
- Quelle vorpriorisieren
- Jede Woche Stichproben bei den False Positive machen. -> Gibt es immer bei den selben Personen False Positive Meldungen?

Solved?
- Stichproben geschlossene Tickets anschauen und entscheiden ob diese richtigerweise geschlossen wurde oder nicht.

Containable in L1

- tichproben ob L1 wirklich richtig entscheidet und nicht fälschlicherweise zu L2 gibt

### RACI - Responsible Accountability Consulted Informed

Dabei werden die Begriffe wie folgt interpretiert:

- Responsible – zuständig für die eigentliche Durchführung (Durchführungsverantwortung). Die Person, die die Initiative für die Durchführung (auch durch Andere) gibt. Sie kann die Aktivität auch selbst durchführen. Wird auch als Verantwortung im disziplinarischen Sinne interpretiert.
- Accountable – rechenschaftspflichtig (Kosten- bzw. Gesamtverantwortung), verantwortlich im Sinne von „genehmigen“, „billigen“ oder „unterschreiben“. Die Person, die im rechtlichen oder kaufmännischen Sinne die Verantwortung trägt. Wird auch als Verantwortung aus Kostenstellensicht interpretiert.
- Consulted – konsultiert. Eine Person, die vielleicht nicht direkt an der Umsetzung beteiligt ist, aber relevante Informationen für die Umsetzung hat und deshalb befragt werden soll oder muss.
- Informed – zu informieren (Informationsrecht). Eine Person, die Informationen über den Verlauf bzw. das Ergebnis der Tätigkeit erhält oder die Berechtigung besitzt, Auskunft zu erhalten.

#### RACI: Einige Beobachtungen

- Achtung: 'Responsible' heisst übersetzt 'Verantwortlich'; trotzdem hat die verantwortliche Partei lediglich die Verantwortung für die Durchführung! Die eigentliche Verantwortung liegt bei der Partei mit 'Accountability'
- Gesamtverantwortung ('Accountability') muss für jede Zeile bestimmt werden 
- Es kann immer nur eine Accountability pro Zeile geben -> wenn Verantwortung geteilt wird nimmt sie niemand mehr wahr…
- Das (RACI) Modell erlaubt es nicht, 'Mitarbeit' darzustellen: wenn mehrere Parteien an einer Tätigkeit arbeiten bleiben die Optionen jeder Partei ein 'R' für ihren Bereich zuzuteilen oder angemessene Kommentare in das RACI einzufügen.

Es gibt ein RASCI Modell, welches ‘Support’ enthält, aber es ist weniger bekannt und akzeptiert.

#### Fallstudie: Erstellen eines RACI

- Wie sind Sie vorgegangen?
- Welche Tätigkeiten haben Sie gewählt? Warum?
- Wie haben sie die Verantwortlichkeiten zugeteilt?
- Wenn Sie das fertige RACI anschauen: welche Aussagen können Sie aufgrund der Muster treffen?

![](img/2021-03-24_22-20-01.png)

![](img/2021-03-24_22-20-39.png)

- Eine mögliche Lösung:

![](img/2021-03-24_22-21-42.png)

- Sehen Sie Probleme in dieser Lösung?

### Incident-, Problem & Change Management

#### Begriffe

- Incident Management (ITIL)
  - Ein Ereignis, das nicht zum standardmäßigen Betrieb eines Services gehört und das tatsächlich oder potenziell eine Unterbrechung dieses Services oder eine Minderung der vereinbarten Qualität verursacht
- Problem Management (ITIL) 
  - Ein Problem ist die Ursache eines oder mehrerer Incidents
- Change Management (ITIL)
  - Prozess, der das Ziel hat, dass alle Anpassungen an der IT-Infrastruktur kontrolliert, effizient und unter Minimierung von Risiken für den Betrieb bestehender Business Services durchgeführt werden
- Security Incident Management 
  - Ein sicherheitsrelevanter Vorfall

#### Incident Management

- Incident Management umfasst typischerweise den gesamten organisatorischen und technischen Prozess der Reaktion auf erkannte oder vermutete Störungen
- Ziel des Incident-Management-Prozesses ist die schnellstmögliche Wiederherstellung der Service-Leistung (auch mit Workarounds)
- Incidents werden in einem Ticketing System dokumentiert und verfolgt
- Für die Entgegennahme und Überwachung der Tickets ist ein Servicedesk zuständig

![](img/2021-03-24_22-24-42.png)

#### Problem Management

- Problem-Management analysiert mögliche oder bereits eingetretene Störungen und identifiziert Ursachen sowie Massnahmen zu ihrer Verhinderung oder Behebung
- Ergebnis ist entweder ein Known Error (der über Change Management behoben wird) oder ein Workaround (Umgehungslösung)
- Im Problem-Management erarbeitete Umgehungslösungen werden im Incident Management verwendet um erneut auftretende Incidents rasch zu lösen

![](img/2021-03-24_22-25-43.png)

#### Incident oder Problem?

Ein oder mehrere 'Ja' deuten auf einen Incident hin:
- Ist der Service nicht verfügbar? 
- Ist der Service eingeschränkt?
- Ist der Geschäftsprozess beeinträchtigt?
- Können Service Levels nicht mehr gewährleistet werden?

![](img/2021-03-24_22-27-24.png)

#### Change Management

- CM erfasst, dokumentiert, genehmigt und überwacht Änderungen und stellt sicher, dass sie geplant, effizient, kostengünstig und mit minimalem Risiko ausgeführt werden
  - Initiieren, Dokumentieren und Autorisieren von Änderungen
  - Einschätzung der Auswirkungen, Kosten, Vorteile und Risiken
  - Genehmigung 
  - Planen und Koordinieren der Implementierung
  - Überwachen und Reporting 
  - Prüfung und abschliessende Bearbeitung von Request for Changes (RfCs)

![](img/2021-03-24_22-29-05.png)

#### IT Security Incident

- Interessanterweise gibt es keine einfach auffindbare, allgemein akzeptierte Definition
- Eine Liste von sicherheitsrelevanten Ereignissen, gesammelt aus mehreren Quellen, zeigt die Bandbreite und damit das Problem mit der Definition:
  - Intrusion oder versuchte Intrusion 
  - Bekanntwerden neuer Sicherheitslücken in bestimmten Anwendungen oder Betriebssystemen 
  - neuartige Viren / Malware 
  - Spam / Phishing 
  - Einbruch

**Ein Ereignis, welches Confidentiality, Integrity oder Availability einer Information oder eines Assets beeinflusst**

### Security Incident Response

#### CSIRT / CERT

- Ein Computer Security Incident Response Team (CSIRT) oder Computer Emergency Response Team (CERT) ist ein Team von IT-Sicherheitsexperten, bzw. -sachverständigen, deren Hauptaufgabe darin besteht, Computersicherheitsverletzungen so schnell als möglich zu erkennen und darauf zu reagieren
- Je rascher ein Zwischenfall erkannt und behandelt wird, desto geringer ist der Schaden
- Dieses Team bietet die zu ihrer Behandlung notwendigen Dienstleistungen und unterstützt bei der Wiederherstellung nach Sicherheitsverletzungen

#### CSIRT Einführung (1/2)

ENISA schlägt die folgenden Schritte zur Implementierung eines CSIRT vor: 
- Verstehen, was ein CSIRT ist und welche Vorteile es bieten könnte 
- Definition, für welchen Bereich CSIRT Services erbringt 
- Definition der CSIRT Services 
- Analyse der Umgebung und der Kunden 
- Definition von Kommunikationswegen & Aufgabenbereichen 
- Finanzierungsmodell bestimmen (Kosten, Ertrag, Finanzierung) 
- Definition der Organisationsstruktur (intern, extern, zentral, dezentral) 
- Rekrutierung der Mitarbeiter, Bereitstellung der Räumlichkeiten und Infrastruktur 
- Erstellung und Genehmigung der Sicherheitsrichtlinien

#### CSIRT Einführung (2/2)

- Suche nach Kooperationspartnern 
- Erstellen des Implementierungs Projektplans 
- CSIRT implementieren:
  - Erstellen der Arbeitsabläufe 
  - Implementieren der CSIRT-Werkzeuge
- Ausbildung und Schulung der Mitarbeiter

#### Incident- und Krisenmanagement

- Ein eigenständiges CSIRT/CERT ist für die meisten Firmen zu teuer
- Stattdessen konzentrieren sich Firmen meist darauf, ein sinnvolles Incidentund Krisenmanagement aufzubauen:
  - Incidents sollen zuverlässig erkannt und behandelt werden
  - Triage weist Incidents den optimalen Bearbeitern zu
  - Eskalation stellt sicher, dass Management und Spezialisten je nach Signifikanz des Incidents miteinbezogen werden.

#### Eskalationskriterien

- Eskalation verfolgt primär zwei Ziele:
  - Benötigte Unterstützung wird bereitgestellt 
  - Management ist informiert, dass Probleme bestehen
- Entsprechend sind die Auslöser für Eskalationen:
  - Kritikalität der betroffenen Assets 
  - Zugriff auf benötigte Ressourcen (meist Spezialisten, evtl. Hardware oder externe Unterstützung)
  - Zeitdauer: je nach Severity des Incidents ist nach einer gewissen Bearbeitungsdauer die nächste Stufe des Managements zu informieren, bzw. sogar die Verantwortung abzugeben.
    - In der Praxis könnte das bedeuten, dass nach 30 Minuten der Teamleiter informiert werden muss. Nach 60 Minuten übernimmt der Teamleiter und informiert seinerseits den Abteilungsleiter sowie den Verantwortlichen für Major Incidents. Nach 90 Minuten wird ein Major Incident ausgerufen, Senior Management und Krisenmanager werden informiert…

#### Eskalationsstufen (1/4)

Je signifikanter und länger andauernd ein Incident ist, desto höher wird er eskaliert

![](img/2021-03-24_22-35-30.png)

#### Eskalationsstufen (2/4)

- Business as Usual (BAU): Alles läuft wie geplant, keine besonderen Vorkommnisse
- Tritt ein Incident ein, sollte er automatisiert oder durch Personen an den Service Desk gemeldet werden. Dieser führt eine erste Beurteilung des Ausmasses durch – bei kritischen Incidents ist eine Eskalation in das Major Incident oder gar Crisis Management möglich. ‘Reguläre’ Incidents werden vom Service Desk an das zuständige, bzw. am besten geeignete Team zugewiesen
- Incident Management bedeutet, dass die Organisation – beginnend mit L1, dann unter Miteinbezug von L2 oder auch L3 – daran arbeitet, den Incident zu beheben.

#### Eskalationsstufen (3/4)

- Nach vorgängig zu definierenden Kriterien wird gegebenenfalls ein Major Incident ausgerufen. Wichtige Aspekte im Major Incident Management:
  - Verantwortlicher Manager bestimmt
  - Autorität, alle nötigen Ressourcen miteinzubeziehen 
  - Autorität, Krisenmanagement einzuleiten 
  - Kommunikationsverantwortlicher bestimmt:
    - regelmässige Information von Management und Stakeholdern
    - Entgegenahme und Beantwortung aller Fragen (Entlastung Incident Manager & Team) 
  - Ereignislogbuch führen 
  - Abschlussbericht erstellen (‘Lessons learned’)

#### Eskalationsstufen (4/4)

- Das Krisenmanagement ist die letzte Eskalationsstufe. Entsprechend ist die Geschäftsleitung miteinbezogen und der Krisenmanager hat Zugriff auf alle benötigten Bereiche der Firma.
- Das Krisenmanagement ist nicht IT- oder Information Security spezifisch sondern wird ganz allgemein benötigt um mit überraschenden Bedrohungen für die Organisation umzugehen, die schnelle Entscheidungen benötigen.
- Aus Sicht IT und Security ist Krisenmanagement von entscheidender Bedeutung für BCM oder wenn Zugriff auf die Rechts- oder Kommunikationsabteilung nötig ist.
- Alle Ebenen von Incident Management sollten regelmässig getestet und verbessert werden, am Wichtigsten ist dies beim Krisenmanagement, da hier Fehler die grössten Auswirkungen haben können und da der Prozess selten benötigt wird.

#### Ausgewählte Kontrollen: Patch Management

![](img/2021-03-24_22-37-09.png)

##### Patch Management Lifecycle & Process

1. Discovery

Comprehensive network inventory & assessment.

2. Categorize & Prioritize

Segment systems and users by risk & priority.

3. Policy Creation & Updates

Develop and update patching requirements.

4. Monitoring for New Patches

Create a patch release tracking system.

5. Patch Testing

Test patches on non-production environments.

6. Configuration Management

Document intended changes and results.

7. Patch Roll Out

Implement patch policy after testing & validation.

8. Patch Auditing

Identify failed, pending patches & compatibility issues.

9. Reporting & Analysis

Create a patch compliance report for stakeholders.

10. Review, Optimize, Repeat

Periodically review and optimize patch policy process.

#### Ausgewählte Kontrollen: IAM

High-Level IAM Architektur

![](img/2021-03-24_22-38-16.png)

#### IAM als fortlaufender Prozess

![](img/2021-03-24_22-38-35.png)

1. Datenlieferant HR
- Stammdaten, Organisationsdaten, Kostenstellen kommen aus der Personalabteilungen
- Quality-Check ist sinnvoll; Schlechte Daten sind für IdM ein Hindernis
  - Minimal: Wer ist wessen Vorgesetzter und wie sieht die Kostenstellenstruktur aus (Workflows)
  
2. Integration von IT-Systemen
- Die IT-Abteilung ist für die Integration der verschiedenen IT-Systeme verantwortlich
- Insbesondere sind das Directory (wie MS AD), Mailsysteme und ERP-Systeme
- Die Integration der Hauptsysteme reicht für eine Quick-Win Lösung vollkommen aus

3. Zugriffskontrolle
- Es muß sichergestellt werden, dass kein unerlaubter Zugriff auf Informationen und Services besteht
- Einbindung der Fachabteilungen in den Entscheidungsprozess
  - Reporting: Wer hatte wann Zugriff und war dieser Zugriff berechtigt?
  
4. Workflows
- Aufbau von Antrags- und Genehmigungsworkflows, um den Verwaltungsaufwand zu senken
- Rollenbasierte Berechtigungsvergabe ist sehr komplex
  - Besser mit Einzelberechtigung ergänzen

5. Provisioning
- Das Provisioning, d.h. Das Schreiben der Identitäten in die Zielsysteme findet automatisiert statt
- Wichtig: Automatische Sperrung, Reaktivierung und endgültige Löschen von Account miteinbeziehen
  - Stichwort: Vermeidung verwaister Benutzerkonten
  
6. Compliance
- Gesetzliche Vorgaben in Regeln für die Vergabe von Benutzer- und Zugriffsrechten übersetzen
- Regeln können dann im Workflow abgebildet und ausgewertet werden
  - Für bereits bestehende Accounts zusätzliche defektives Reporting implementieren

7. Re-Zertifizierung von Accounts
- Regelmäßige Verifizierung und Prüfung von Accounts ist notwendig
- Vorgänge und geschäftsabläufe werden transprent gemacht und unbefugte Tätigkeiten erkannt

8. Unternehmensrollen
- Gesetzliche Vorgaben rücken die firmenweite Verwaltung von IT-Berechtigungen auf Basis von
- Rollen der Mitarbeiter in der Fokus der Unternehmen.
- Mit Role-Mining wird eine Optimierung und Bereinigung von Unternehmensrollen durchgeführt

**IdM ist kein einmaliges Ereignis, sondern ein fortlaufender Prozess**

#### IAM Präventive Controls

![](img/2021-03-24_22-38-51.png)

#### Ausnahmeerkennung und Behandlung

![](img/2021-03-24_22-39-04.png)

## Nachbearbeitung

https://moodle.ffhs.ch/mod/assign/view.php?id=3731200

---

# 4 Nachhaltiger Betrieb und Verbesserung

###### Lernziele

Ich weiss wie ein Security Monitoring aufgebaut und gehandhabt wird.

Ich weiss wie Risiken nachhaltig verwaltet werden können.

Ich kann Reifegradmodelle für Sicherheit erklären und anwenden. (Wie misst man Sicherheit?)

Ich kenne Methoden zur kontinuierlichen Qualitätsverbesserung.

Ich kann ein Programm zur Implementierung der IT Sicherheitsstrategie inkl. deren Massnahmen unterhalten und Massnahmen zur Optimierung erkennen und vorschlagen.

## Vorbereitung

https://moodle.ffhs.ch/mod/assign/view.php?id=3731206

## Präsenz

Dauer	Thema
15'	Fragen zur Vorbereitung
20'	Präsentation der Gruppenarbeit  (Gruppe c)
30' IT Security Monitoring
30'	Diskussion und Wiederholung Risk- & Exception Management 
30'	Lehrgespräch Incident-, Problem- und Change Management
15' Pause
30'	Maturity Model CMMI zur Reifegradmessung
30'	Continuous Improvement mittels Key Performance Indicators (KPI) sowie den Plan-Do-Check-Act (PDCA) Zyklus
15'	Didaktischer Puffer

### Agenda
- Diskussion der Aufgabe Fallstudie Prozessdesign
- Security Monitoring n Risk- und Exception Management
- Maturity Model CMMI zur Reifegradmessung
- Continuous Improvement mittels Key Performance Indicators (KPI) sowie dem Plan-DoCheck-Act (PDCA) Zyklus

![2021-05-08_10-11-07](img/2021-05-08_10-11-07.png)

### Diskussion der Aufgabe 'Fallstudie Prozessdesign'

#### Lösen der Fallstudie
- Gab es Schwierigkeiten? Welche?

- Spezialität

Dieser Prozess hat 2 Eintrittspunkte: er wird sowohl durch eine neue Vulnerability als auch monatlich ausgelöst

- Checkpunkte:
    - Der Prozess kann nicht in einen undefinierten Zustand kommen (‘Error Handling’)
    - Es gibt immer (mindestens) einen Start und der Prozess führt immer zu einem Endpunkt
    - Jede Entscheidung hat einen ‘Ja’ und einen ‘Nein’ Ausgang

##### Musterlösung

![2021-05-08_10-12-21](img/2021-05-08_10-12-21.png)

### IT Security Monitoring

#### SIEM: Begriff
- Security Information and Event Management (SIEM) ist ein Begriff für Software Produkte und Services, die Security Information Management (SIM) und Security Event Management (SEM) verbinden.
- Security Information Management (SIM) bezeichnet die Sammlung von Daten (typischerweise Logs) in einem zentralen Repository um Trendanalyse durchzuführen.
  - Datensammlung
- Ein Security Event Management (SEM) System kann Logs analysieren um Ereignisse oder Verhaltensweisen zu identifizieren.
  - Datenanalyse

#### SIEM: Eigenschaften

- Data Aggregation: Daten verschiedener Herkunft werden konsolidiert und aggregiert (Beispiel: Anzahl failed Logins über einen Tag)
- Correlation: Daten werden in Bezug zueinander gesetzt um Muster zu erkennen (Beispiel: Login eines Benutzers während Ferien)
- Alerting: Auftreten eines Events oder Erreichen eines Thresholds wird alarmiert (Konsole, Dashboard, Ticket, Email, …)
- Dashboards: Visualisierung der im SIEM gespeicherten Events und Alerts um Analysten zu helfen, Muster zu erkennen oder Incidents zu analysieren

- Compliance: ein SIEM kann die Einhaltung von Standards prüfen und auf Abweichungen aufmerksam machen
- Retention: historische Daten erlauben Langzeit-Analysen (Empfehlung 2 Jahre)
- Forensics: Unterstützung von forensischen Analysen

#### SIEM Produkte
-  Die 'grossen' Produkte sind
    - ArcSight (HP)
    - QRadar (IBM)
    - Splunk (Splunk)
- Für eine kleinere Firma oder bei beschränktem Budget kann es sinnvoll sein, erste Erfahrungen mit einem Open Source SIEM zu sammeln:
    - OSSIM
    - LOGalyze
    - Build your own (Artikel ist in Moodle verfügbar): http://www.sans.org/reading-room/whitepapers/incident/creating-siem-incident-response-toolkit-open-source-tools-33689

![2021-05-08_10-13-39](img/2021-05-08_10-13-39.png)

#### SIEM Produkte: Unruhiger Markt
Neu von Microsoft: Sentinel

![2021-05-08_10-14-26](img/2021-05-08_10-14-26.png)

![2021-05-08_10-14-43](img/2021-05-08_10-14-43.png)

### Big Picture: Logging & SIEM
![2021-05-08_10-15-32](img/2021-05-08_10-15-32.png)

#### Bottom-up Ansatz
- Verfügbare Logs sammeln
- Logs und eigene Umgebung verstehen
  - Was ist normal?
- Monitoring Regeln entwickeln
  - Use Case bestimmt

![2021-05-08_10-52-17](img/2021-05-08_10-52-17.png)
- Time to market
- Hohe Qualität, da Konzentration auf Kompetenzen

![2021-05-08_10-52-41](img/2021-05-08_10-52-41.png)
- Sicherheitsbedarf der Unternehmung nur intuitiv berücksichtigt
- Möglicherweise nur punktuelle Abdeckung
- Lücken nicht bekannt
- Regeln und Use Cases werden oft sehr spezifisch, also nicht wiederverwendbar implementiert

#### Top-Down Ansatz: Threat Model
- Basierend auf dem Fleckenteppich, den ermittelten Risk Ratings und unseren Möglichkeiten können wir nun unsere Aktivitäten priorisieren

![2021-05-08_10-52-17](img/2021-05-08_10-52-17.png)
- Der Fleckenteppich visualisiert unseren gewünschten Schutzbedarf und unseren aktuellen Abdeckungsgrad
  - Das Management hat eine Indikation zur Gefährdung

![2021-05-08_10-52-41](img/2021-05-08_10-52-41.png)
- Die Analyse als solche verbessert noch nichts – sie hilft uns nur, die beschränkten Ressourcen risikobasiert einzusetzen

![2021-05-08_10-18-10](img/2021-05-08_10-18-10.png)

#### Integration
- Das Threat Model ermöglicht, das Monitoring risikobasiert aufzubauen und zu verbessern.
- Die spezifische Implementation folgt weiterhin dem Bottom-up Ansatz (obtain --> understand --> build --> optimize).
  - Die Kombination generiert längerfristig Mehrwert

![2021-05-08_10-18-36](img/2021-05-08_10-18-36.png)

#### Logmanagement
- Quantität --> Erhalten wir die benötigten Log Events aller abzudeckenden Systeme?
    - Reagieren auf Deckungslücken
    - Erkennen von Anomalien (Flooding, Fehlen von Event Types)
- Qualität --> Sind die Log Events verständlich?
    - Können Log Events nicht parsed / verarbeitet werden?
    - Sind Teile von Log Events nicht vorhanden oder nicht verständlich?
- Abdeckung --> Wie viele Aspekte der Use Cases decken wir ab?
    - Was ist das Restrisiko?
    - Beispiel Unauthorized Change: Erkennen wir einen Change, erkennen wir authorized changes, können wir das in allen Plattformen / Feeds?

#### Monitoring
-  Monitoring und Incident Management sind typischerweise Kernaufgaben des Security Operations Center (SOC).
- Monitoring beinhaltet Reaktion auf SIEM Alarme, aber auch proaktive Überwachung und Identifikation von Vorfällen, die das SIEM nicht erkennt.
- Proaktiv erkannte Incidents sollten als Verbesserung in das SIEM einfliessen.
- Die Beurteilung und Bearbeitung von Security Incidents erfolgt durch Menschen:
  - Es ist wichtig, gut ausgebildete Spezialisten zur Verfügung zu haben
  - Fehler bei der False / True Positive Triage werden nicht mehr gesehen (Stichwort: False Negatives)
  - True Positives werden durch Analysten behandelt. Folgen sie angemessen den Prozessen, führen sie eine korrekte Root Cause Analyse durch? è Manuelle Qualitätssicherung für beide Fälle notwendig

#### Security Monitoring – Overview

![2021-05-08_10-19-25](img/2021-05-08_10-19-25.png)

#### Incident Management
- SOC behandelt Incidents nach definierten Prozessen welche, abgestuft nach Kritikalität der Incidents, bestimmen welche Stellen miteinbezogen werden müssen und welche Reaktionszeiten einzuhalten sind.
- Eine mögliche Definition der Kritikalität könnte sein:
  - Normale Incidents betreffen keine kritischen Komponenten und können ohne Miteinbezug von Spezialisten oder Management gelöst werden
  - Eskalierte Incidents betreffen kritische Komponenten, benötigen die Fachkenntnis von Spezialisten oder führen zu einer Änderung von Systemen (Change Control)
  - Notfälle beeinträchtigen die Gesundheit oder Sicherheit von Menschen oder sind Sicherheitsbrüche in kritischen Systemen

(Vergleichen Sie dazu auch das Beispiel 'Security Incident Management', welches wir im Teil 'Prozessdesign' behandelt haben)

### Risk- und Exception Management

#### Weshalb Risk Management?
- Bisher haben wir Risiken ausschliesslich auf taktischer Ebene behandelt; z.B. um den aktuellen Schutzbedarf zu ermitteln und daraus Kontrollen abzuleiten.
- Nachhaltige Behandlung von Risiken bedingt eine strategische Herangehensweise
- Die Komplexität der Strategie reicht von regelmässiger Durchführung der taktischen Schritte bis zur Bildung einer Risikomanagement Organisation und Definition eines Risikomanagement Prozesses

>Nachhaltigkeit ist ein Handlungsprinzip zur Ressourcen-Nutzung, bei dem die Bewahrung der wesentlichen Eigenschaften, der Stabilität und der natürlichen Regenerationsfähigkeit des jeweiligen Systems im Vordergrund steht.

#### Definition
- Risikomanagement umfasst sämtliche Massnahmen zur systematischen Erkennung, Analyse, Bewertung, Überwachung und Kontrolle von Risiken.
- Unter Risikomanagement versteht man den planvollen Umgang mit Risiken.
- Risikomanagement umfasst die Phasen Risikoidentifikation, Risikobewertung, Risikosteuerung und Risikokontrolle. Analog dem Managementkreis werden die Phasen wiederholt durchlaufen und stellen somit einen Zyklus dar.
- Ebenso wichtig, aber nicht explizit erwähnt, ist das Exception Management

Wikipedia

http://de.wikipedia.org/wiki/Risikomanagement

#### Risikoidentifikation
- Zusammenstellung einer Liste der verschiedenen Risiken.
- Mögliche Quellen:
  - Threat Model
  - Listen von Gefährdungen
  - Experten befragen
  - Kreativitätstechniken
  - Auswertung von Incidents
  - Externe Quellen (Nachrichten, Security Communities, Fachkollegen)

#### Risikobewertung
- Zusätzlich zur Bewertung von Einzelrisiken soll ein Risikomanagement auch die Kumulation (oder auch: Aggregation) von Risiken behandeln.
- Grundgedanke ist, dass eine Summe von verhältnismässig geringen, auf den ersten Blick vielleicht noch nicht einmal direkt verbundenen Risiken, in einem inakzeptablen Gesamtrisiko resultieren kann.
- Kombiniert man z.B. die unten ausgeführten, für sich noch akzeptablen Risiken, wird ersichtlich, dass die Gefahr von Viren und Malware den Risikoappetit überschreitet:
    - Virenschutz ist implementiert aber nicht alle Agents funktionieren ordnungsgemäss und neue Signaturen werden nur wöchentlich eingespielt.
    - Kritische und wichtige Patches werden nicht so schnell ausgebreitet, wie es die Unternehmenspolitik vorschreibt.
    - Das IDS ist nicht optimal konfiguriert, generiert daher zu viele False Positives und das SOC kann nicht alle Alarme zeitnah bearbeiten.

#### Risikosteuerung
- **Residual Risk**: Durch geeignete Massnahmen wird das Risiko auf ein Mass gesenkt (Eintretenswahrscheinlichkeit oder Ausmass), welches im Rahmen der Risikobereitschaft des Unternehmens liegt.
- **Risk Appetite**: Die Risikobereitschaft ergibt sich aus der Strategie, welche vom Management bestimmt wird.
- **Exception**: Falls Risiken für einen gewissen Zeitraum nicht auf ein akzeptables Mass reduziert werden können ist dies formell zu dokumentieren und zu genehmigen.
- **Risk Avoidance & Risk Acceptance**: Wenn Risiken nicht auf ein akzeptierbares Mass reduziert werden können bleiben die Optionen, das Risiko zu vermeiden, oder es zu akzeptieren. Eine Acceptance muss nicht zwangsläufig terminiert sein, sollte aber trotzdem regelmässig revalidiert werden.

#### Risikosteuerung
- Die Risikobewertung gibt Hinweise, welche Strategie für ein bestimmtes Risiko die Vorteilhafteste ist:

![2021-05-08_10-22-30](img/2021-05-08_10-22-30.png)

#### Risk Appetite
- Gemäss ISO 31000 is Risikoappetit das ‘Ausmass von Risiken, die eine Unternehmung bereit ist zu akzeptieren’.
- Betriebswirtschaftlich ergibt sich der Risikoappetit aus dem Profit, der erwirtschaftet werden kann, wenn ein Risiko eingegangen wird: Sind die erwarteten Kosten bei Eintreten des Risikos geringer als der erwartete Profit, befinden wir uns innerhalb des Risikoappetits der Unternehmung.

![2021-05-08_10-23-08](img/2021-05-08_10-23-08.png)

#### Risikosteuerung
![2021-05-08_10-23-38](img/2021-05-08_10-23-38.png)

#### Risikokontrolle
- Risiken sind in einem Risk Inventar zu dokumentieren.
- Dokumentation aller Vorgänge, die im Zusammenhang der Risikoanalyse, -beurteilung, -verminderung und -revalidierung stattfinden.
- Zu jedem Risiko sollten Aktionspläne zur Eliminierung oder zumindest Verringerung des Risikos bestehen.
- Risiken sind regelmässig zu prüfen:
    - Werden die Aktionspläne zeitgerecht und gewissenhaft abgearbeitet?
    - Sind die Risiken noch korrekt bewertet?
    - Bestehen nicht akzeptable aggregierte/kumulierte Risiken?
    - Sind Ausnahmen (Exceptions) abgelaufen ohne dass die Risiken eliminiert wurden?
    - Sind die Risk Acceptances noch gerechtfertigt?
- Aus der Prüfung lassen sich Risikoindikatoren (KPI) ermitteln

### Maturity Model CMMI (Reifegradmessung)

#### Definition CMMI
1986 im Auftrag des US Verteidigungsministeriums als System zur Bewertung der Reife von Softwareprozessen erstellt, ist das Capability Maturity Model Integration (CMMI) heute in Version 1.3 (2010) eine Familie von Referenzmodellen für unterschiedliche Anwendungsgebiete – derzeit für die Produktentwicklung, den Produkteinkauf und die Serviceerbringung.

Ein CMMI-Modell ist eine systematische Aufbereitung bewährter Praktiken, um die Verbesserung einer Organisation zu unterstützen. Ein CMMI-Modell kann genutzt werden, um

- einen Überblick über bewährte Praktiken (z. B. bei der Projektplanung) zu bekommen,
- die Stärken und Schwächen einer Organisation objektiv zu analysieren oder
- Verbesserungsmassnahmen zu bestimmen und in eine sinnvolle Reihenfolge zu bringen.

#### Anwendung von CMMI
- Alle Modelle sind sich einig, dass die Qualität gemessen und laufend verbessert werden soll
- CMMI beschreibt Maturity Levels auf eine leicht zugängliche und anschauliche Art und ist daher Quasi-Standard für Reifegradmessung
- Wir behandeln CMMI nicht in der Tiefe, wollen aber (aktiv und passiv) mit den Maturity Levels vertraut sein

#### Reifegrade
- Unser Fokus liegt auf Serviceerbringung: CMMI ist ein Ansatz, um die Maturität unserer Prozesse zu bestimmen und damit Verbesserungspotential zu identifizieren
- Es ist NICHT Ziel, immer und in jedem Fall Level 5 Maturity zu erreichen: die Verwaltung der Parkplätze ist nicht annähernd so sensitiv wie z.B. die Sauberkeit eines Operationssaals!

![2021-05-08_10-24-46](img/2021-05-08_10-24-46.png)

1. Initialzustand

2. Prozess **existiert und kann wiederholt** werden.
- Die Zeiten sind einigermassen vorhersehbar
- Kosten und Qualität unterliegen starken Schwankungen

3. Prozess **eingeführt und dokumentiert**.
- Kosten und Zeiten vorhersehbar
- Qualität unterliegt Schwankungen

4. Prozess wird **geführt und gesteuert**.
- Für den Prozess und die Ergebnisse werden Ziele vorgegeben, Erreichung wird gemessen und überwacht.
- Zeiten, Kosten und Qualität sind zuverlässig kontrollierbar

5. Prozess wird **kontinuierlich verbessert**.
- Für Prozess und Ergebnisse werden Optimierungsziele vorgegeben, Erreichung wird gemessen und überwacht. Zeiten, Kosten und Qualität kontrollierbar

#### Maturity Levelshttps://cmmiinstitute.com/learning/appraisals/levels
Maturity levels represent a staged path for an organization’s performance and process improvement efforts based on predefined sets of practice areas. Within each maturity level, the predefined set of PA’s also provide a path to performance improvement. Each maturity level builds on the previous maturity levels by adding new functionality or rigor.

- Maturity Level 0: **Incomplete**

Ad hoc and unknown. Work may or may not get completed.

- Maturity Level 1: **Initial**

Unpredictable and reactive. Work gets completed but is often delayed and over budget.

- Maturity Level 2: **Managed**

Managed on the project level. Projects are planned, performed, measured, and controlled.

- Maturity Level 3: **Defined**

Proactive, rather than reactive. Organization-wide standards provide guidance across projects, programs, and portfolios.

- Maturity Level 4: **Quantitatively Managed**

Measured and controlled. Organization is data-driven with quantitative performance improvement objectives that are predictable and align to meet the needs of internal and external stakeholders.

- Maturity Level 5: **Optimizing**

Stable and flexible. Organization is focused on continuous improvement and is built to pivot and respond to opportunity and change. The organization’s stability provides a platform for agility and innovation.

#### Fallstudie CMMI
![2021-05-08_10-25-23](img/2021-05-08_10-25-23.png)

![2021-05-08_10-25-50](img/2021-05-08_10-25-50.png)

![2021-05-08_10-26-15](img/2021-05-08_10-26-15.png)

#### Fallstudie CMMI 'Benutzerberechtigungen'
![2021-05-08_10-26-39](img/2021-05-08_10-26-39.png)

| Prozessbeschreibung                                                                                                                                                                                                       | Maturity |
|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:---------|
| Der Administrator vergibt Benutzerberechtigungen wenn er darum gebeten wird.                                                                                                                                              | 1        |
| Es besteht eine Prozessdokumentation, welche definiert wer unter welchen Voraussetzungen welche Zugriffe erhalten darf. Es besteht ein Manual, welches erklärt, wie die Berechtigungsvergabe im System durchzuführen ist. | 2        |
| Die Dokumentation definiert zusätzlich, wie und wo die Anträge und Approvals zu dokumentieren sind. Es bestehen Vorgaben, wie rasch Änderungen durchzuführen sind.                                                        | 3        |
| Key Controls sind definiert und ihre Erreichung wird mit SLA gemessen und rapportiert. Management ergreift Schritte, wenn SLA verfehlt werden.                                                                            | 4        |
| Es werden Wege gesucht, den Prozess zu verbessern oder zu automatisieren. Entsprechende Aktionen werden eingeleitet und ihre Erreichung gemessen.                                                                         | 5        |

### Continuous Improvement: KPI

#### Provide Actionable Risk Intelligence
Proposal of 16 Security Metrics for Implementation

- The following 16 metrics were identified as the most relevant metrics for CIO.
- All 5 NIST security domains are covered.

![2021-05-08_10-27-34](img/2021-05-08_10-27-34.png)

##### Identify
- % of applications with incomplete or outdated Asset Inventory data (i.e. criticality rating or other critical fields)
- % of applications not compliant to risk assessment cycles (RtB; CtB; IAST; IFA Pentest)
- \#  of EOL assets (i.e. servers) that have not been through LCM assessment (LCM = Life Cycle Management)
- \#  of assets without any connection or not delivering the required data to central logging and monitoring tools

##### Protect
- % of used Infrastructure not following Baseline Security (Tripwire) or with exceptions
- \# of weak or not assessed Vendors
- % of applications not compliant in Access Management cockpit or MyAccess
- \#  of applications without tested communication and disaster recovery plans (resiliency)
- \#  of applications hosted on infrastructure without EDR (Endpoint Detection and Respond) control

##### Detect
- \#  of people who click links in malicious / phishing emails (clickers; not simulated phishing attackl)
- \#  of assets with exception to scanning

##### Respond
- % of risk items identified during project but did not get remediated before going live of the asset
- \#  of Past Dues / Expired risk items
- \#  of overdue high rated vulnerabilities (speed of patching)
- Deviation in total number of high risk exceptions (e.g. Lumension exception; DLP exception)

##### Recover
- \# of desktop rebuilds


#### Definition
Der Begriff Key Performance Indicator (KPI) bzw. Leistungskennzahl bezeichnet in der Betriebswirtschaftslehre Kennzahlen, anhand derer der Fortschritt oder der Erfüllungsgrad hinsichtlich wichtiger Zielsetzungen oder kritischer Erfolgsfaktoren innerhalb einer Organisation gemessen und/oder ermittelt werden kann.

http://de.wikipedia.org/wiki/Key_Performance_Indicator

#### Metrik – KPI – SLA
- Metrik: Eine Metrik, ist eine (meist mathematische) Funktion, die eine Eigenschaft von Software in einen Zahlenwert abbildet.
    - \# Restages/Monat, % roter Risiken in einem Projekt
- Key Performance Indicator (KPI): Leistungskennzahl bezeichnet Kennzahlen, anhand derer der Erfüllungsgrad hinsichtlich wichtiger Zielsetzungen oder kritischer Erfolgsfaktoren gemessen werden kann.
- Service Level Agreement (SLA): Für die Messung der in SLAs definierten Kennzahl für das erreichte Serviceniveau (Servicelevel oder Servicegrad) werden KPI herangezogen.
  - Oft Prozentwerte, immer mit Zielen für Grün, Gelb, Rot

#### Bestimmen von KPI
- Zielsetzungen / Erfolgsfaktoren
    - Ergeben sich aus den Anforderungen des Kunden an den Service
        - \>= 95% der Patches innerhalb Zeitvorgaben installiert
        - \>= 80% der infizierten Workstations innert 48h neu installiert
        - \>= 90% der Call Center Anrufe in 30 Sekunden angenommen
- Prozesse
    - Wo Key Controls nicht automatisiert erzwungen werden können sollten sie gemessen werden
        - Keine Freigabe einer Zahlung durch Erfasser der Zahlung
        - Keine Änderung in Systemen ohne Change Ticket
        - <= 3% Emergency Changes für Software und Betriebssysteme
    - Oft sehr strikte SLA Vorgaben, da Prüfung der Einhaltung von Vorschriften (Compliance)
- Werte (Bandbreiten) für Grün, Gelb und Rot bestimmen

#### Definition sinnvoller KPI
SMART: Nicht spezifisch für KPI, aber trotzdem ein guter Ansatz

http://de.wikipedia.org/wiki/SMART_(Projektmanagement)

|    | Deutsch     | English      | Beschreibung                                                                                                                   |
|:---|:------------|:-------------|:-------------------------------------------------------------------------------------------------------------------------------|
| S  | Spezifisch  | Specific     | Ziele müssen eindeutig definiert sein (nicht vage, sondern so präzise wie möglich)                                             |
| M  | Messbar     | Measurable   | Ziele müssen messbar sein (Messbarkeitskriterien)                                                                              |
| A  | Akzeptiert  | Assignable   | Ziele müssen von den Empfängern akzeptiert werden/sein (auch: angemessen, attraktiv, abgestimmt ausführbar oder anspruchsvoll) |
| R  | Realistisch | Realistic    | Ziele müssen erreichbar sein                                                                                                   |
| T  | Terminiert  | Time-related | Zu jedem Ziel gehört eine klare Terminvorgabe                                                                                  |

#### KPI: Beispiele

| +                                                                                                 | -                                                 |                     |
|:--------------------------------------------------------------------------------------------------|:--------------------------------------------------|:--------------------|
| 95% der bewilligten Berechtigungen werden innert 2 Arbeitstagen implementiert                     | Anzahl Logins ausserhalb Bürozeiten               | Messwert, kein Ziel |
| RTO (Return to Operation) eines Servers wird in 97% der Fälle erreicht                            | 100% der Vireninfektionen werden verhindert       | Unrealistisch       |
| 98.5% Verfügbarkeit des Services innerhalb Betriebszeiten (geplante Ausfälle sind nicht relevant) | Maximal 50% False Positive Alerts aus dem IDS     | Nicht sinnvoll      |
| SOC beginnt Bearbeitung aller Security Incidents (100%) innert 45 Minuten                         | Sicherheit der Systeme ist sichergestellt         | Nicht messbar       |
| 95% der Patches werden innerhalb der Zeitvorgaben eingespielt (98% für kritische Server)          | Patches werden zeitnah analysiert und eingespielt | Nicht spezifisch    |

#### Einführen von KPI
- Definition
    - Definition der KPI
    - Bestimmen der Verantwortlichkeiten (wer misst wann, wer ist für die Erreichung des Ziels verantwortlich, an wen wird rapportiert und eskaliert)
- Datenbeschaffung
    - Welche Daten werden benötigt und wie können sie (möglichst automatisiert) beschafft und bearbeitet werden
    - Wo und für wie lange werden die Basisdaten und KPI gespeichert
- Baselining
  - Wie gut erreichen wir das KPI Ziel heute
  - Erreichbare KPI Ziele vereinbaren (evtl. Verbesserung planen)
- Betrieb
  - Messen, Rapportieren, Eskalieren falls Ziele nicht erreicht werden

#### Auswerten / Rapportieren
- Maximaler Nutzen ergibt sich bei regelmässiger Messung und Interpretation der Ergebnisse über eine gewisse Zeitspanne
- Visualisierung ist sehr wichtig für effektive Kommunikation: neben spezialisierten Tools kann aber auch z.B. Excel adäquate Ergebnisse liefern
- Wiederholte Nicht-Erreichung von KPI muss untersucht werden:
    - Ungewöhnliche Umstände?
    - Ziele unrealistisch?
    - Probleme?

![2021-05-08_10-30-35](img/2021-05-08_10-30-35.png)

#### Auswerten / Rapportieren
- Sobald ein gewisser Grundstock an KPI definiert und regelmässig gemessen wird macht es Sinn, die Ergebnisse empfängergerecht auszuweisen:
    - Management will wenige, aussagekräftige KPI sehen
    - Service Manager und Spezialisten sind interessiert an detaillierteren Informationen
- Logisch zusammengehörige KPI können für unterschiedliche Empfänger konsolidiert werden:

![2021-05-08_10-31-04](img/2021-05-08_10-31-04.png)

![2021-05-08_10-31-28](img/2021-05-08_10-31-28.png)

#### Metriken: Praxisbeispiele
![2021-05-08_10-32-32](img/2021-05-08_10-32-32.png)

![2021-05-08_10-32-49](img/2021-05-08_10-32-49.png)

#### KPI: Praxisbeispiel
![2021-05-08_10-33-23](img/2021-05-08_10-33-23.png)

### Continuous Improvement: PDCA
William Edwards Deming (1900 – 1993) war ein US-amerikanischer Physiker, Statistiker sowie Pionier im Bereich des Qualitätsmanagements

#### Geschichte
- Deming promovierte 1928 zum Doktor der mathematischen Physik und lehrte danach an verschiedenen Universitäten und arbeitete von 1927-1949 als mathematischer Physiker für das Landwirtschaftsministerium.
- 1950 holte ihn General Douglas MacArthur als Statistiker und Qualitätsexperte nach Japan wo er seine – in den USA weithin unbeachteten Erkenntnisse – den Topmanagern Japans bekannt machte. Im Toyota-Produktionssystem sind Demings Ideen schon sehr früh auf fruchtbaren Boden gefallen. Deming und seine Erkenntnisse wurden erst 1980 nach der Ausstrahlung einer NBC Dokumentation mit dem Titel ’If Japan can... Why can’t we?’ in den USA wahrgenommen.
- Deming fasste seine Erkenntnisse in einem 14-Punkte-Programm für besseres Management, 7 Hürden für die Umsetzung der neuen Philosophie und den 7 tödlichen Krankheiten eines Managementsystems zusammen. Neben der Demingschen Reaktionskette wird auch die Beschreibung des PDCA-Zyklus (Plan Do Check Act) Deming zugeschrieben. Deming selbst wies jedoch darauf hin, dass Walter A. Shewhart diesen als erster beschrieben hatte.

#### Plan – Do – Check – Act
- Der PDCA Zyklus oder Deming-Kreis ist eine Systematik zur kontinuierlichen Verbesserung
- Der PDCA-Zyklus beschreibt die Phasen im kontinuierlichen Verbesserungsprozess, der Grundlage aller Qualitätsmanagement-Systeme
- Es wird eine stetige Verbesserung der Prozesse und Abläufe verfolgt um die Effizienz, Kunden- und Mitarbeiterzufriedenheit des Unternehmens zu verbessern.

![2021-05-08_10-34-24](img/2021-05-08_10-34-24.png)

#### Plan – Do

##### Plan

Der Prozess muss vor seiner eigentlichen Umsetzung geplant werden. Plan umfasst
- das Erkennen von Verbesserungspotentialen (in der Regel durch den Arbeiter, beziehungsweise Teamleiter vor Ort)
- die Analyse des aktuellen Zustands sowie das Entwickeln eines neuen Konzeptes (unter intensiver Einbindung des Arbeiters)

##### Do

Do bedeutet nicht die Einführung und Umsetzung auf breiter Front, sondern das Ausprobieren, beziehungsweise Testen und praktische Optimieren des Konzeptes mit schnell realisierbaren, einfachen Mitteln (z.B. provisorische Vorrichtungen) an einem einzelnen Arbeitsplatz (wieder unter starker Einbindung des Arbeiters (Gemba)

#### Check – Act

##### Check

Der im Kleinen realisierte Prozessablauf und seine Resultate werden sorgfältig überprüft und bei Erfolg für die Umsetzung auf breiter Front als Standard freigegeben.

##### Act

Hier wird der neue Standard auf breiter Front eingeführt, festgeschrieben und regelmässig auf Einhaltung überprüft (Audits).

Dies kann eine 'grosse Aktion' sein, die umfangreiche organisatorische Aktivitäten, die Durchführung von Schulungen, Anpassung von Aufbau- und Ablauforganisation) sowie erhebliche Investitionen (an allen vergleichbaren Arbeitsplätzen, in allen Werken) umfassen kann.
- Die Verbesserung dieses Standards beginnt wiederum mit der Phase Plan.

#### PDCA: Standardize
- Nach jedem PDCA-Zyklus sind die Massnahmen durch einen SDCA-Zyklus zu standardisieren. Nach jeder Einführung eines festgelegten Standards (Standardize), wird dieser Standard praktiziert (Do), das Verfahren auf Richtigkeit und Funktionstüchtigkeit überprüft (Check) und bei Notwendigkeit geändert (Action). Diese Action ist dann im Regelfall das Planen eines weiteren PDCA-Zyklus. …

![2021-05-08_10-35-13](img/2021-05-08_10-35-13.png)


## Nachbearbeitung

https://moodle.ffhs.ch/mod/assign/view.php?id=3731212

---

# 5 Business Continuity, Audit & Recht

###### Lernziele

Ich weiss um die Wichtigkeit der Ursachen-Analyse und kann sie anwenden.

Ich kann den Nutzen einer Notfallvorsorge aufzeigen und organisatorische und technische Voraussetzungen für eine bedarfsgerechte Umsetzung erläutern.

Ich habe ein grundsätzliches Verständnis der IT Forensik und weiss, welche Anforderungen beachtet werden müssen.

Ich kann Grundbegriffe der Revision (Audit) erläutern.

Ich kenne die wichtigsten schweizerischen Gesetzesnormen mit Einfluss auf IT Sicherheit.

## Vorbereitung

https://moodle.ffhs.ch/mod/assign/view.php?id=3731215

## Präsenz

Dauer	Thema
10'	Fragen zur Vorbereitung
20'	Präsentation der Gruppenarbeit  (Gruppe B)
15' Prozessdesign
30'	Analyse und Darstellung von Verantwortlichkeiten (RACI)
30' Incident-, Problem- und Change Management
15' Pause
30'	IT Security Monitoring
30'	Security Incident Response
15'	Didaktischer Puffer

## Nachbearbeitung

https://moodle.ffhs.ch/mod/assign/view.php?id=3731223

---
# Zusammenfassugen - IT Security Management

## Kapitel 1 - Schutzziele und Schutzbedarf

Sicherheit bezeichnet einen Zustand, der als weitgehend frei von Gefahren oder unvertretbaren Risiken angesehen werden kann. IT-Sicherheit zielt darauf ab, das Gefahrenpotenzial für
geschäftsrelevante Daten und Informationen, die durch ICT-Systeme gespeichert und verarbeitet werden, auf ein tragbares (verkraftbares) Niveau zu senken.

Der Datenschutz bezweckt den Schutz der Daten und Informationen vor Missbrauch, unberechtigter Einsichtnahme, Verwendung, Änderung oder Verfälschung (Manipulation). Unter
das Datenschutzgesetz fallen v.a. sensible, personenbezogene Daten.

Die Datensicherheit bezweckt den umfassenden Schutz der Daten und InformationWT
bezüglich Vertraulichkeit, Integrität, Verfügbarkeit und Verbindlichkeit.

Die Datensicherung umfasst alle organisatorischen und technischen Vorsorgemassnahmen,
um die Vertraulichkeit, Integrität, Verfügbarkeit und Verbindlichkeit sicherzustellen. Es geht
also um Massnahmen, die verhindern sollen, dass diese Schutzziele verletzt werden.

Die Notfallvorsorge umfasst alle personellen, organisatorischen und technischen Vorsorgemassnahmen, die bei Störungen zum Tragen kommen, die die Vertraulichkeit, Integrität, Verfügbarkeit und Verbindlichkeit beeinträchtigen. Es geht also um Massnahmen, die umgesetzt werden müssen, wenn diese Schutzziele bereits verletzt worden sind.

Eine Bedrohung ist ein mögliches Ereignis, das zu einem Schaden führen kann. Bedrohungen
lassen sich zu verschiedenen Kategorien zusammenfassen. Ein Risiko ist eine Bedrohung, die
so wahrscheinlich ist (oder erscheint), dass mit dem Eintreffen des Ereignisses gerechnet
werden muss. Eine Verletzbarkeit, ist ein Mangel an einem Objekt bzw. eine Anfälligkeit
eines Objekts in Bezug auf bestimmte Schutzziele. Um Risiken bewerten zu können, müssen
das Schadenpotenzial und die Eintrittswahrscheinlichkeit berücksichtigt werden.

Im Rahmen der Risikoanalyse ist das Zusammenwirken von Bedrohung, Verletzbarkeit,
Schadenpotenzial und Eintrittswahrscheinlichkeit von Bedeutung. Folgende Grafik soll die
Zusammenhänge dieser Faktoren verdeutlichen:

![Schema der Risikoanalyse](img/Schema%20der%20Risikoanalyse.png)

Um die ermittelten Risiken bzw. mögliche Schäden zu vermeiden oder zu verringern, sind darauf abgestimmte Sicherheitsmassnahmen notwendig.

Sicherheitsbedürfnisse und Risikobereitschaft der Unternehmen sind unterschiedlich ausgeprägt und hängen u.a. von folgenden Einflussfaktoren ab: aktuelles und künftiges Angebot an Produkten und Dienstleistungen, Prozesse, Organisationsform, Produktionsmethoden, Umwelt und Unternehmensstrategie. Auf der einen Seite müssen Geschäftsprozesse bzw. deren Teilprozesse diverse Anforderungen an die IT-Sicherheit erfüllen. Auf der anderen Seite erhöhen Sicherheitsmassnahmen i.d.R. die Komplexität eines Geschäftsprozesses und reduzieren seine Durchlaufgeschwindigkeit. Sie hemmen demzufolge auch die Effizienz und Effektivität des Geschäftsprozesses. Entsprechend müssen Sicherheitsmassnahmen so gestaltet und integriert werden, dass das gewünschte Sicherheitsniveau erreicht wird, ohne den Prozess über Gebühr zu beeinträchtigen. Die Informatik alleine schafft es nicht, die Sicherheitsbedürfnisse eines Unternehmens zu erfüllen. Um das gewünschte Sicherheitsniveau zu erreichen, müssen alle Mitarbeitenden und Bereiche des Unternehmens Zusammenarbeiten.

Auf der Basis von technischen und organisatorischen Standards lassen sich nicht nur die spezifischen Sicherheitskriterien ableiten, sondern auch das Sicherheitsniveau eines Unternehmens beurteilen. Sie werden deshalb auch als Kontrollmodelle eingesetzt, um den aktuellen Stand der IT-Sicherheit zu prüfen.

###  Management-Tipps

Der IT-Sicherheitsbeauftragte eines Unternehmens ist nur selten in der Lage, Einfluss auf Bedrohungen zu nehmen. Er kann jedoch wohl beeinflussen, welche Bedrohungen zu Risiken werden. Durch konkrete Aussagen, was im Unternehmen als schützenswert gilt, legt der IT-Sicherheitsbeauftragte den Grundstein für effektive und effiziente Sicherheitsmassnahmen.
Auf diese Weise können alle notwendigen Kräfte gebündelt werden, um geschäftskritische Risiken abzuwehren. Das Business Continuity Management soll die Wetterführung der Geschäftsprozesse auch im Fall betrieblicher Störungen gewährleisten. Voraussetzung dafür ist, dass klar definiert wird, welche Prozesse unbedingt aufrechterhalten werden müssen und welche Massnahmen dafür notwendig sind.


## Kapitel 2 - Gesetze, Standards und Regelwerke

Diverse Schweizer Gesetze und Verordnungen sowie internationale Standards und Regelwerke stellen Anforderungen an die IT-Sicherheit, aus denen sich die unternehmerischen Sicherheitsziele und betrieblichen Schutzbedürfnisse ableiten:

- Im OR werden die Aufgaben und die Verantwortung der Geschäftsleitung festgelegt. Daraus lassen sich insbesondere Kontroll- und Aufsichtspflichten, aber auch Sorgfaltspflichten im Umgang mit Daten und Informationen ableiten.
- Im DSG werden die Rechte und Pflichten der Inhaber von Personendatensammlungen geregelt. Die betroffenen Personen haben weitgehende Rechte zur informationellen Selbstbestimmung, d.h., sie können bestimmen, was der Inhaber der Datensammlung mit «ihren» Daten machen darf und was nicht.
- Im StGB wird geregelt, welche Handlungen verboten sind und ob es sich dabei um Antrags- oder Offizialdelikte handelt. Bei Antragsdelikten muss das Opfer aktiv werden und eine Anzeige erstatten. Bei Offizialdelikten werden die Behörden aktiv und verfolgen den Straftatbestand automatisch, sofern sie davon Kenntnis haben. Geregelt werden auch die Delikte im Zusammenhang mit Computerkriminalität.
- In der GebüV wird die korrekte und sachgemässe Aufbewahrung von Geschäftsunterlagen geregelt. Diese Verordnung enthält konkrete Anforderungen bezüglich der Archivierung von Geschäftsunterlagen.
- Im ZertES wird geregelt, welche Anforderungen ein Anbieter von Zertifikaten erfüllen muss, die für qualifizierte digitale Signaturen verwendet werden.
- Im BÜPF wird die Überwachung des Post- und Fernmeldeverkehrs geregelt.
- Das URG enthält Bestimmungen im Zusammenhang mit dem Schutz von Urheberrechten.

Best Practices und Standards sind hilfreiche Instrumente, um gesetzliche oder branchenspezifische Anforderungen an die IT-Sicherheit einzuhalten. Sie stellen operationalisierbare Ziele und konkrete Handlungsanweisungen zur Verfügung, um die betriebliche IT-Sicherheit ganzheitlich und systematisch umzusetzen:

- CoblT steht für Control Objectives for Information and Related Technology und ist ein anerkanntes Rahmenwerk für die IT-Governance, d.h. für die Beherrschung bzw. Steuerung der gesamten Informatik in einem Unternehmen.
- ISO/IEC 27001 richtet sich an Organisationen jeglicher Art und definiert Anforderungen an ein systematisches IT-Sicherheitsmanagementsystem (ISMS) unter Berücksichtigung von Risiken.
- ITIL hat sich zum Standard für das Servicemanagement in der Informatik durchgesetzt. Mit ISO/IEC 20000 gibt es auch einen ISO/IEC-Standard zum IT-Servicemanagement.
- BSI-Grundschutzmethode systematisiert die Bedrohungen durch ICT-Systeme und stellt standardisierte Sicherheitsmassnahmen zur Auswahl, um ein ausbaufähiges Mindestniveau an IT-Sicherheit zu gewährleisten.
- Common Criteria stellt Kriterien für die Bewertung der Sicherheit von Computersystemen oder -komponenten zur Verfügung.
- OSSTMM ist eine frei verwendbare Methode für die Planung, Durchführung und Dokumentation technischer Sicherheitsaudits.
- FIPS 140 kann für die Zertifizierung von Produkten und Verfahren im Bereich der Kryptografie herangezogen werden.

Neben Best Practices und Standards, die sich allgemein an Organisationen richten, gibt es branchenbezogene Regelwerke, die von Aufsichtsbehörden, Branchenverbänden oder -vereinen für «ihre» Branche entwickelt bzw. herausgegeben werden.

### Management-Tipps
Im Rahmen des IT-Sicherheitsmanagements müssen alle relevanten Gesetze, Standards und Regelwerke mit Bezug zur IT-Sicherheit identifiziert und deren Anforderungen berücksichtigt werden.(Compliance). Unternehmen, die im internationalen Umfeld tätig sind, müssen auch internationale und lokale Gesetze in den entsprechenden Ländern berücksichtigen. Die Standards mit Bezug zur IT-Sicherheit wurden in den letzten Jahren konsolidiert. Die Wahl der passenden und anwendbaren Standards sowie die Festlegung des Umsetzungsgrads im eigenen Unternehmen gehört zur Verantwortung des Managements. Es ist durchaus möglich, verschiedene Standards im Unternehmen gleichzeitig einzusetzen. Um Mehrspurigkeiten bei der Analyse, Planung, Umsetzung, Kontrolle und Verbesserung der IT-Sicherheit zu vermeiden, ist jedoch darauf zu achten, dass die Ziele der Standards aufeinander abgestimmt werden.

## Kapitel 3 - Sicherheitsanforderungen und -aufgaben

Die Sicherheitsanforderungen eines Unternehmens stammen von externen und internen Anspruchsgruppen. Externe Sicherheitsanforderungen werden von aussen an Unternehmen herangetragen, beispielsweise über Gesetze, Branchenverbände, Kunden oder Lieferanten. Interne Sicherheitsanforderungen stammen aus den Prozessen und Fachabteilungen des Unternehmens und werden hauptsächlich aus der Unternehmensstrategie abgeleitet.

Mithilfe eines Anforderungskatalogs lassen sich die erhobenen Anforderungen schriftlich festhalten und übersichtlich darstellen. Der Anforderungskatalog kann später auch als Grundlage für die Beurteilung der Risiken und des angestrebten Sicherheitsniveaus herangezogen werden. Standards und Best Practices können bei der Erstellung des Anforderungskatalogs und bei der Verifizierung der Sicherheitsanforderungen behilflich sein. Entschliesst sich ein Unternehmen, nach einem bestimmten Standard zu arbeiten, sind die dort angeführten Sicherheitsanforderungen und -kriterien verbindlich.

Der IT-Sicherheitsbeauftragte ist prinzipiell für die Wahrnehmung aller Belange der IT-Sicherheit innerhalb eines Unternehmens zuständig. Seine Funktion, Aufgaben und Kompetenzen sind aber nicht einheitlich, sondern variieren von Unternehmen zu Unternehmen. Je nach Grösse des Unternehmens bzw. je nach Art und Umfang der eingesetzten ICT-Systeme übernimmt er z. B. eher Kontroll- und Überwachungsaufgaben oder sorgt persönlich für die Planung und Umsetzung der notwendigen Sicherheitsmassnahmen. Die Hauptaufgabe des IT-Sicherheitsbeauftragten besteht darin, die Geschäftsleitung bei der Erfüllung der Sicherheitsanforderungen zu beraten und bei der Umsetzung zu unterstützen.

Neben dem IT-Sicherheitsbeauftragten braucht es eine schlagkräftige und tragfähige Organisation, um die IT-Sicherheit im Unternehmen zu gewährleisten. Grundlegende Voraussetzung für die Etablierung und Bewirtschaftung wirksamer Sicherheitsstrukturen und -prozesse ist ein systematisches Informationssicherheits-Managementsystem (ISMS). Für den Auf- und Ausbau des ISMS eignet sich ein IT-Sicherheitsforum. Dieses Führungsgremium ist mit entsprechenden Befugnissen auszustatten und interdisziplinär zusammenzustellen.

Wenn ein Unternehmen über grosse Datensammlungen verfügt, die unter das DSG fallen, kann die Einsetzung eines internen Datenschutzbeauftragten angezeigt sein. Im Rahmen der Notfallvorsorge werden Arbeitsteams vorgesehen, die bestimmte Notfälle oder Risiken bezüglich der IT-Sicherheit bewältigen müssen. Ein solches Notfallteam wird einberufen, sobald ein bestimmter Notfall eintritt oder wenn das Unternehmen durch ein bestimmtes Ereignis bedroht wird. Ein ISMS besitzt Schnittstellen zu anderen Systemen wie dem Risikomanagement und dem internen Kontrollsystem (IKS) eines Unternehmens, mit dem Abstimmungsaktivitäten durchgeführt werden müssen.

### Management-Tipps

Das Bekenntnis eines Unternehmens, und somit dessen Management, zu IT-Sicherheit manifestiert sich in der Etablierung einer Organisation für IT-Sicherheit, in diesem Fall ISMS genannt. Mit einer solchen Organisation werden durch das Management die notwendigen Ressourcen, Verantwortlichkeiten und Kompetenzen für die IT-Sicherheit zugewiesen.

Diesem ISMS erteilt das Management die entsprechenden Aufträge und stellt die notwendigen, konkreten Anforderungen bezüglich der IT-Sicherheit auf. Es obliegt auch dem Management, im Endeffekt die zu verwendenden Standards, Methoden und Vorgehensmodelle auszuwählen und für das Unternehmen verbindlich festzulegen. Es ist Aufgabe des Managements, die daraus resultierenden Arbeitsergebnisse im Rahmen der IT-Sicherheit zu würdigen und zu vertreten.

## Kapitel 4 - Methoden und Techniken

Der PDCA-Zyklus ist eine Methode für die kontinuierliche Prozessverbesserung, wobei PDCA für die Phasen Plan (Planen), Do (Umsetzen), Check (Prüfen) und Act (Handeln) steht.

Im Rahmen der Risikoanalyse werden die IT-Sicherheitsrisiken ermittelt und bewertet. Idealerweise wird die Risikoanalyse in ein systematisches Risikomanagement eingebunden. Der Zweck der Risikoanalyse besteht darin, die für ein Unternehmen oder für einen bestimmten Untersuchungsbereich relevanten Risiken zu ermitteln und zu bewerten. Während das grundsätzliche Vorgehen immer dasselbe bleibt, unterscheiden sich je nach Untersuchungsbereich die zu analysierenden Objekte und Prozesse und entsprechend auch die Bewertungskriterien. Bei der Vorbereitung der Risikoanalyse ist die Risikoanalyse zu initiieren und der Untersuchungsbereich ab- bzw. einzugrenzen. Bei der Durchführung der Risikoanalyse sind die Risiken zu identifizieren und zu bewerten.

Für die Risikoidentifikation stehen Kollektionsmethoden, analytische Suchmethoden und Kreativitätsmethoden zur Verfügung. In der Praxis können Risiken nicht immer losgelöst von anderen Risiken betrachtet werden. Sie können voneinander abhängig sein, sich gegenseitig beeinflussen, zu einer Erhöhung des Gesamtrisikos oder sogar zu neuen Risiken führen. Zur Aufdeckung solcher Abhängigkeiten eignet sich die Darstellung in Form einer Risikomatrix.

Nachdem die wesentlichen Risiken für den definierten Untersuchungsbereich identifiziert worden sind, müssen sie bewertet werden. Die Risikobewertung stellt die Beurteilung der identifizierten Risiken sicher, indem sie deren negative Auswirkungen quantitativ und/oder qualitativ bemisst. Bei quantitativen Bewertungsverfahren erfolgt die Bewertung der identifizierten Risiken, indem das zu erwartende Schadenausmass anhand einer absoluten Bewertung der Auswirkungen (z. B. in CHF) beschrieben wird. Bei qualitativen Bewertungsverfahren erfolgt die Bewertung der identifizierten Risiken, indem das zu erwartende Schadenausmass anhand einer relativen Ein- oder Zuordnung beschrieben wird. Bei der Auswahl des Verfahrens zur Risikobewertung gilt es u.a. zu beachten, wie genau das Schadenpotenzial berechnet werden muss.

Um die bewerteten Risiken eines oder mehrerer Untersuchungsbereiche übersichtlich darzustellen, eignet sich auch die sogenannte Risk Map. Diese Darstellungstechnik verschafft einen raschen Überblick über die wichtigsten Risiken, indem die identifizierten Risiken entsprechend ihres Schadenpotenzials und ihrer Eintrittswahrscheinlichkeit angeordnet werden. Die beliebtesten Diagrammtypen im Rahmen der Risikoanalyse sind das Netz- und das Blasendiagramm.

Die Business-Impact-Analyse bildet die Grundlage für die unternehmerische Sicherheitsstrategie und die betriebliche Notfallvorsorge im Rahmen des Business Continuity Managements (BCM). Bei der Business-Impact-Analyse werden mögliche Auswirkungen untersucht, die durch einen ausgefallenen Geschäftsprozess für ein Unternehmen entstehen können. Zu diesem Zweck werden mögliche Ausfallszenarien (z. B. «Szenario Wassereinbruch») entworfen und im aktuellen organisatorischen Umfeld durchgespielt. Solche Szenarien können sich grundsätzlich auf alle Schutzziele der Datensicherheit beziehen (Vertraulichkeit, Verfügbarkeit, Integrität, Verbindlichkeit).

Die Strukturanalyse dient zur systematischen Erhebung der IT-Infrastruktur und bildet die Grundlage für die Ermittlung des Schutzbedarfs nach der BSI-Grundschutzmethode. Die Strukturanalyse kann in folgende Schritte gegliedert werden: Netzplan erheben, Komplexität durch Gruppenbildung reduzieren, Infrastrukturkomponenten erheben, Komponenten pro Applikation erfassen, Schutzbedarf für Anwendungen feststellen, Schutzbedarf für Komponenten feststellen, Schutzbedarf für Kommunikationsverbindungen feststellen, Schutzbedarf für Räume feststellen, Ergebnisse interpretieren.

### Management-Tipps

Die IT-Sicherheitsbeauftragte muss nicht nur die Standards für das IT-Sicherheitsmanagement bestimmen, sondern auch die anzuwendenden Methoden und Techniken festlegen. Es liegt in der Verantwortung des Managements die ausgewählten Standards, Methoden und Techniken unternehmensweit zu vereinheitlichen und zu kommunizieren.

## Kapitel 5 - Sicherheitsstrategie und Sicherheitskonzept erstellen

Die Unternehmensstrategie befasst sich mit der mittel- bis langfristigen Ausrichtung des Unternehmens und zeigt auf, wie die Erfolgschancen erhalten bzw. ausgebaut und die Misserfolgsrisiken vermieden bzw. reduziert werden sollen. Die IT-Strategie leitet sich aus der Unternehmensstrategie ab und zeigt den Weg auf, wie die Informations- und Kommumkationstechnologien zugunsten des Unternehmenserfolgs einzusetzen sind. Eine «intelligente» IT-Strategie zeichnet sich durch folgende Eigenschaften aus:

- Sie trägt zum Wachstum bei, indem sie neue Märkte oder Geschäftsfelder erschliesst.
- Sie trägt zum Wachstum bei, indem sie neue Geschäftsprozesse ermöglicht.
- Sie trägt zur Effektivitätssteigerung bei, indem sie wichtige Beiträge zur Zielerreichung liefert.
- Sie trägt zur Effizienzsteigerung bei, indem sie die Geschäftsprozesse unterstützt und optimiert.

Die IT-Sicherheitsstrategie sagt aus, wie ein Unternehmen die internen und externen Sicherheitsanforderungen erfüllen will, ohne dass dem Unternehmen daraus Nachteile erwachsen. Sie leitet sich sowohl von der Unternehmensstrategie als auch von der IT-Strategie ab und kann mit einem «Gesetz» verglichen werden, das vorschreibt, was punkto IT-Sicherheit alles zu beachten ist. Die IT-Sicherheitsstrategie trifft Aussagen zu den wesentlichen Schutzzielen des Unternehmens und regelt in groben Zügen die damit verbundenen Verantwortlichkeiten. Daneben beinhaltet sie auch Aussagen zur Risikobewältigungsstrategie. Anhand dieser Vorgaben können sämtliche Aktivitäten abgeleitet werden, die mit der IT-Sicherheit Zusammenhängen. Die IT-Sicherheitsstrategie stellt somit gleichzeitig Leitfaden und Legitimitätsgrundlage für unternehmerische Sicherheitsaktivitäten dar, indem sie wegweisende und nachprüfbare Vorgaben dazu macht.

Das Sicherheitskonzept zeigt auf, wie ein Unternehmen die Vorgaben der IT-Sicherheitsstrategie umsetzen will. Hier wird beschrieben, welche Risiken mit welchen Massnahmen bekämpft werden und welche organisatorischen Rahmenbedingungen gelten. Es ist sozusagen das «Kochbuch» der IT-Sicherheitsbeauftragten für die Erfüllung der Sicherheitsanforderungen. Ein IT-Sicherheitskonzept muss den unternehmerischen Realitäten angepasst und laufend optimiert werden. Vor der erstmaligen Erstellung eines IT-Sicherheitskonzepts müssen folgende Voraussetzungen geschaffen werden:

- Bewertung der Risiken, die mit den bestehenden oder geplanten Geschäftsprozessen und Applikationen verbunden sind
- Festlegung der Risikobewältigungsstrategie
- Auswahl angemessener Sicherheitsmassnahmen

Um zu gewährleisten, dass im IT-Sicherheitskonzept alle Sicherheitskriterien und -anforderungen berücksichtigt werden, muss ein geeignetes Kontrollmodell implementiert werden. Standards wie z.B. CoBIT stellen spezifische Kontrollmodelle mit prozessbezogenen Steuerungsvorgaben (Control Objectives) für die IT-Sicherheit zur Verfügung.

### Management-Tipps
Ohne Unternehmensstrategie mit klaren Aussagen zu den mittel- bis langfristigen Chancen und Risiken fehlt die Grundlage für eine IT-Sicherheitsstrategie und somit auch für ein schlüssiges IT-Sicherheitskonzept. Es liegt in der Verantwortung des Managements, Vorgaben in Bezug auf die IT-Sicherheit zu machen, an denen sich die IT-Sicherheitsbeauftragten orientieren können und an denen ihre Arbeit gemessen werden kann. Daneben muss das Management sicherstellen, dass die einzelnen Strategien aufeinander abgestimmt und den Verantwortlichen kommuniziert werden. Eine fortlaufende Kontrolle sowie die aktive Unterstützung des IT-Sicherheitskonzepts durch das Management kann sichergestellt werden, indem die Geschäftsleitung jede neue Version dieses Dokuments offiziell prüfen und verabschieden muss.

## Kapitel 6 - Risiken analysieren, Schutzbedarf feststellen, Schwachstellen aufdecken

Damit der IT-Sicherheitsverantwortliche darüber Auskunft geben kann, welche Bedrohungen für sein Unternehmen Sicherheitsrisiken darstellen, müssen Analysen durchgeführt werden.

Im Rahmen der allgemeinen Risikoanalyse werden folgende Aktivitäten durchgeführt:

![IMG_5999](img/IMG_5999.png)

Für die Identifikation der Sicherheitsrisiken im Rahmen der Business-Impact-Analyse werden realistische und allgemein formulierte Szenarien herangezogen. Wichtige Sicherheitsrisiken aus Prozesssicht betreffen i. d. R. die Schutzziele Verfügbarkeit und Integrität. Es können aber auch Szenarien definiert werden, die die Vertraulichkeit betreffen.

Mithilfe der BSI-Grundschutzmethode kann untersucht werden, welche Unternehmensbereiche einen besseren Schutz benötigen. Zu diesem Zweck wird zunächst eine Strukturanalyse durchgeführt. Dabei werden ein Netzplan erhoben und die vorhandenen Systeme, Applikationen, Kommunikationsverbindungen und Räume auf ihren Schutzbedarf hin untersucht. Danach wird der Schutzbedarf der Applikationen festgestellt und nach dem Vererbungsprinzip an die zugehörigen Systeme, Kommunikationsverbindungen und Räume weitergegeben. Dabei gilt das Maximumprinzip, d. h., die Systemkomponente mit dem höchsten Schutzbedarf ist für den Schutzbedarf des Gesamtsystems massgebend. Zeichnet sich bei einer Komponente ein erhöhter Schutzbedarf ab, so muss diese im Rahmen einer Risikoanalyse genauer untersucht werden. Ansonsten sind die entsprechenden Massnahmen nach dem BSI-Grundschutz umzusetzen.

Mittels CobIT-Kontrollmodell kann sichergestellt werden, dass die IT-Prozesse und IT-Ressourcen des Unternehmens im Einklang mit den Sicherheitsanforderungen und übergeordneten Zielen des Unternehmens stehen. Bestehende Sicherheitslücken können im Rahmen eines Self-Assessments anhand eines CRSA-Formulars aufgedeckt werden. Für die Beurteilung der Risiken werden die Bedeutung und der Erfüllungsgrad der IT-Prozesse ausgewiesen.

### Management-Tipps

Die Analyse der Risiken, Schutzbedürfnisse und Sicherheitslücken sind operative Tätigkeiten, die durch die entsprechenden Fachabteilungen vorgenommen werden müssen. Das Management ist dafür verantwortlich, dass die notwendigen Ressourcen und richtigen Personen mit dem entsprechenden Fachwissen zur Verfügung gestellt werden. Es gehört zu den Aufgaben der IT-Sicherheitsverantwortlichen dafür zu sorgen, dass die Analysen mit der notwendigen Sorgfalt durchgeführt werden.

## Kapitel 7 - Managementsystem für IT-Sicherheit entwickeln

Das ISMS ist die organisatorische Plattform für die IT-Sicherheit des Unternehmens. Für die zielgerichtete Führung und Steuerung des ISMS müssen bestimmte Managementprinzipien eingehalten werden. Für die IT-Sicherheit müssen die benötigten Ressourcen zur Verfügung gestellt werden. Eine der wichtigsten Ressourcen sind die Mitarbeitenden. Diese müssen in das ISMS eingebunden werden, da sie die IT-Sicherheit tragen und umsetzen müssen. Ein weiteres wichtiges Element ist ein Sicherheitsprozess, der dafür sorgt, dass die betriebliche IT-Sicherheit fortlaufend verbessert und nachhaltig weiterentwickelt wird. Im Rahmen dieses Sicherheitsprozesses muss auch die IT-Sicherheitsstrategie gepflegt werden, die durch das IT-Sicherheitskonzept umgesetzt wird. Für die Kontrolle der Überwachungsziele aus dem Sicherheitskonzept können entsprechende Standards herangezogen werden. Die Wirkung und der aktuelle Stand des unternehmerischen ISMS müssen stufen- und zielgruppengerecht kommuniziert sowie dokumentiert werden.

Damit Verbesserungen in das ISMS einfliessen können, müssen Sicherheitsvorfälle systematisch gesammelt und ausgewertet werden. Automatische Überwachungs- und Detektionssysteme unterstützen den IT-Sicherheitsbeauftragten bzw. den Systemverantwortlichen bei dieser Aufgabe. Für die effektive und effiziente Bearbeitung der Sicherheitsvorfälle werden eine Beweisstcherung und ein Eskalationsplan benötigt. Eine konsistente Auswertung der Sicherheitsvorfalle unterstützt die Qualitätssicherung und zeigt auf, wo welche Massnahmen nicht gegriffen haben.

### Management-Tipps

Die Implementierung und die Aufrechterhaltung eines ISMS ist eine zentrale Aufgabe des Managements in Bezug auf die IT-Sicherheit. Die IT-Sicherheitsbeauftragte hat die notwendigen Schritte einzuleiten, zu überwachen und mit Nachdruck einzufordern. Diese Verantwortung lässt sich nicht delegieren, sondern ist fester Bestandteil der Führungsaufgabe im Unternehmen.

Die IT-Sicherheitsstrategie repräsentiert das Bekenntnis der Unternehmensleitung, in die IT-Sicherheit zu investieren und entsprechende Massnahmen zu unterstützen. Daraus abgeleitete Richtlinien und Vorschriften sind zentrale Grundlagen für ein funktionierendes ISMS. Ohne die entsprechenden Dokumente ist kein ISMS möglich. Doch gerade die Dokumentation wird von den Mitarbeitenden oft als einengend empfunden. Diesem Umstand muss die IT-Sicherheitsbeauftragte ein besonderes Augenmerk schenken.

## Kapitel 8 - Sicherheits- und Notfallmassnahmen entwickeln

Es gibt kein verbindliches, abschliessendes Massnahmenbündel für die unternehmerische IT-Sicherheit. Das Ergebnis wäre eine uniforme und starre Sicherheit, die nicht den gewünschten Nutzen bringt. Es stehen jedoch diverse Massnahmenvorschläge zur Auswahl, die sich in der Praxis bewährt haben und als Grundlage für ein Sicherheitskonzept herangezogen werden können. Typische Vertreter dafür sind die Grundschutzbausteine nach BSI oder die Massnahmenkataloge gemäss ISO/IEC 17799. Welcher Standard auch immer herangezogen wird, am Schluss müssen die ausgewählten Massnahmen umgesetzt werden.

Die Notfallvorsorge zeigt das Vorgehen auf, wenn die umgesetzten Sicherheitsmassnahmen nicht oder nur ungenügend greifen und dadurch ein Notfall eintritt. Fachabteilungen müssen ihre Anforderungen an die Notfallvorsorge definieren und der IT-Sicherheitsverantwortliche muss die entsprechenden Notfallmassnahmen aufeinander abstimmen.

Das Notfallkonzept besteht aus einem Notfallhandbuch, das Notfallpläne für verschiedene Szenarien enthält und den Ablauf und die Zuständigkeiten regelt. Die Notfallpläne müssen regelmässig aktualisiert und durchgespielt werden. Voraussetzung dafür ist, dass die entsprechenden Massnahmen vorgängig implementiert worden sind. Eine reine Datensicherung auf Band genügt dabei in vielen Fällen nicht mehr. Es müssen sowohl die Applikationsarchitektur, die Systemarchitektur und die Funktionalitäten der Datenhaltungssysteme mit berücksichtigt werden. Im Bereich der Systemarchitektur können Massnahmen wie Redundanz, Kaltstart, Warmstart oder Hot-Fallback eingesetzt werden. Moderne Ansätze setzen auf die zunehmende Virtualisierung von Systemlandschaften. Notfallarchive und Wartungsverträge bilden wirksame flankierende Massnahmen zur Notfallvorsorge.

Nicht jedes Unternehmen kann es sich leisten, sämtliche Risiken selber abzusichern. Eine Versicherung kann daher ein Notfallkonzept sinnvoll ergänzen. Welche Risiken auf diese Weise ausgelagert werden, kann der Risikobewältigungsstrategie entnommen werden.

### Management-Tipps

Business Continuity Management ist eine Managementaufgabe, welche die Verantwortung beinhaltet, den Systembetrieb auch bei massiven Störungen aufrechtzuerhalten. Übersteigt der Aufwand zur Behebung einer Störung die eigenen Ressourcen im Unternehmen, tritt ein Notfall ein. Nach dieser Faustregel kann die Grenze zwischen einer Störung und einem Notfall selber bestimmt und entsprechend gesteuert werden. Im Rahmen der Notfallplanung kümmert sich der IT-Sicherheitsbeauftragte um die fachbereichsübergreifende Koordination der Notfallmassnahmen.

## Kapitel 9 - Sicherheitsmassnahmen aufeinander abstimmen

Für die Bewältigung bestimmter Risiken genügt i. d. R. keine Einzelmassnahme. Vielmehr ist ein Bündel von Massnahmen notwendig. Umgekehrt kann sich eine bestimmte Massnahme gleichzeitig auf mehrere Risiken auswirken. Es gibt also keine 1:1 -Beziehung zwischen Risiken und Massnahmen. Aus diesem Grund kann die Analyse verschiedener Risiken zu gleichen oder ähnlichen Massnahmen führen.

Massnahmen lassen sich nach bestimmten Kriterien zusammenfassen. Eine Zusammenfassung nach Risikowirkung ist etwa bei veränderter Risikolage oder bei der Überprüfung neuer Massnahmen hilfreich. Durch eine Gliederung nach Verantwortung kann die Risikobewältigung einzelnen Fachbereichen zugeordnet werden. Massnahmen können aber auch nach Einsatzzweck in vorbeugende, aufdeckende bzw. korrigierende und lenkende Massnahmen eingeteilt werden.

Die Kosten für die Sicherheitsmassnahmen gegen bestimmte Risiken dürfen nicht höher sein als das Schadenausmass gemäss Risikoanalyse. Ansonsten würde eine Art von Überversicherung entstehen. Voraussetzung für die Berechnung der Wirtschaftlichkeit einer Sicherheitsmassnahme ist eine interne Kostenrechnung, die es erlaubt, die Kosten verursachergerecht zu verteilen. Generell steigen die Kosten für die IT-Sicherheit mit dem angestrebten Sicherheitsniveau nicht linear, sondern exponentiell. Die Kosten werden in einem Risikobudget konsolidiert. Auf dieser Grundlage entscheidet die Geschäftsleitung, welche Massnahmen umgesetzt werden und welche Restrisiken bewusst getragen werden.

Im Sicherheitsprogramm werden mehrere Sicherheitsmassnahmen zusammengefasst und koordiniert bzw. aufeinander abgestimmt. Das Sicherheitsprogramm bildet die Grundlage für die einzelnen Realisierungspläne. Es kann für ein Unternehmen ziemlich gefährlich und teuer werden, Sicherheitsmassnahmen zu planen, ohne das entsprechende Bewusstsein bei den Mitarbeitenden zu fördern. Dies kann mithilfe von Trainingsprogrammen oder Schulungen geschehen.

### Management-Tipps

Der IT-Sicherheitsbeauftragte muss sicherstellen, dass diejenigen Sicherheitsmassnahmen ausgewählt werden, die dem Sicherheitsbedarf des Unternehmens entsprechen. Das angestrebte Sicherheitsniveau kann erreicht werden, indem die zur Auswahl stehenden Sicherheitsmassnahmen nach bestimmten Kriterien gegliedert und aufeinander abgestimmt werden. Gegebenenfalls muss auch die Wirtschaftlichkeit der Sicherheitsmassnahmen abgeklärt werden. Hat sich das Management für die Umsetzung bestimmter Massnahmen sowie für die zu tragenden Restrisiken entschieden, müssen entsprechende Sicherheitsprogramme und Realisierungspläne verabschiedet werden. Wichtiger Bestandteil solcher Programme und Pläne sind begleitende Massnahmen zur Förderung des Sicherheitsbewusstseins.

## Kapitel 10 - Personelle Massnahmen planen und umsetzen

Jeder Mitarbeiter stellt ein mögliches lT-Sicherheitsrisiko dar. Besonders augenfällig wird dies bei Systemen, ie ein hohes Mass an Interaktion zwischen Mensch und Maschine erlauben bzw. fordern. Sowohl der Administrator als auch die Benutzer eines ICT-Systems können bewusst oder unbewusst Fehler machen, die grossen Schaden anrichten.

Personelle Sicherheitsmassnahmen fangen bei der Rekrutierung und Auswahl der Mitarbeitenden an. Je klarer die Aufgabengebiete in Form von Stellenbeschreibungen vorliegen, desto besser kann eine Stelle besetzt werden. Zusammen mit dem Arbeitsvertrag können neuen Mitarbeitenden Sicherheitsweisungen zur Unterschrift vorgelegt werden. Gleichzeitig können auch Vertreterregelungen und - mit externen Mitarbeitenden - ggf. Non-Disclosure-Agreements vereinbart werden.

Unwissenheit und Fahrlässigkeit sind die häufigsten Ursachen für Schadenereignisse. Aus diesem Grund müssen die Mitarbeitenden während der Anstellung entsprechend betreut und weitergebildet werden, d. h., es sollten regelmässige Sicherheitsschulungen durchgeführt werden. Als flankierende Massnahmen für die Ausübung sicherheitskritischer Funktionen kommen geeignete Präventions- oder Reaktionsmassnahmen infrage. Empfohlen wird auch eine zentrale Anlaufstelle für die Meldung von Störungen und sicherheitsrelevanter Vorfälle. Bei vorsätzlichem Fehlverhalten müssen Verfahren und Abläufe etabliert sein, die in schwerwiegenden Fällen zu disziplinarischen Massnahmen führen.

Ebenso so geordnet wie die Anstellung muss der Austritt von Mitarbeitenden erfolgen. Dabei muss sorgfältig überprüft werden, welche Nutzungsrechte geändert oder gesperrt werden müssen und welche Daten, Dokumente, Geräte, Schlüssel und Zugangskarten etc. zurückzugeben sind.

### Management-Tipps

Im Bereich der personellen Sicherheitsmassnahmen trägt das Personalmanagement eine entscheidende Verantwortung. Es stellt sicher, dass das richtige Personal eingestellt und dass die disziplinarische Verantwortung wahrgenommen wird. Dies kann nur funktionieren, wenn das Personalmanagement aktiv aus dem Management der Fachabteilungen unterstützt und mit den richtigen Informationen beliefert wird. Das Personalmanagement kann nicht über alle fachlichen Inhalte einer Stellenbeschreibung urteilen. Hier muss auch die Fachabteilung die Verantwortung übernehmen. Das Management ist somit verantwortlich, dass die Funktion des Personalmanagements aktiv genutzt und unterstützt wird. Leider wird in der Praxis oft das Personalwesen mit dem strukturierten und administratiyen Vorgehen auch als Ver- oder Behinderer angesehen. Wie schön wäre es in manchen Fällen, wenn Mitarbeiter A kurzfristig im Team B mitarbeiten und gleichzeitig noch das Team C unterstützen könnte. Wie schöne wäre es, eine Mitarbeiterin kurzfristig für die Überbrückung von Spitzenlasten unbürokratisch und schnell einstellen zu können. Die Kehrseite eines solchen Vorgehens wäre jedoch die Umgehung von wichtigen Sicherheitsmassnahmen, was die gesamte IT-Sicherheit unterwandern könnte.

## Kapitel 11 - Organisatorische Massnahmen planen und umsetzen

Die wichtigste organisatorische Massnahme ist die Etablierung eines ISMS. Damit wird der Grundstein für eine nachhaltige IT-Sicherheit gelegt. Im Rahmen des ISMS sind alle nötigen Sicherheitskonzepte fürabgrenzbare Sicherheitsbereiche zu definieren. Diese regeln grundsätzliche Sicherheitsaspekte und stellen sicher, dass Sicherheitsmassnahmen im ganzen Unternehmen gleich gehandhabt werden. Typische Beispiele für Sicherheitskonzepte sind:

- Virenschutzkonzept
- Wireless-Communication-Konzept
- Dateiablagekonzept
- Berechtigungs-/Logging-Konzept
- Standardarbeitsplatz-Konzept
- Peer-to-Peer-Kozept
- Dokumentationskonzept
- Schlüsselverwaltungskonzept
- Systemmanagementkonzept

Sicherheitsweisungen regeln das konkrete Verhalten der Mitarbeitenden in wichtigen Sicherheitsfragen. In folgenden Bereichen werden Weisungen empfohlen:

Mögliche Bereiche für Sicherheitsweisungen:

![IMG_5970 copy](img/IMG_5970%20copy.png)

Für die Verwaltung der Konzepte, Weisungen und Sicherheitsdokumente kommen i.d.R. Dokumentenmanagementsysteme, das Internet oder Wikis zum Einsatz.

Eine weitere organisatorische Sicherheitsmassnahme ist ein Life-Cycle-Management, das die Einhaltung der Sicherheitsanforderungen über den gesamten Lebenslauf eines Systems hinweg gewährleistet. Das LCM fängt mit der Beschaffung oder Entwicklung an, umfasst den Betrieb und die Wartung (inkl. Konfigurations-, Change-, Release-, Incident- und Problemmanagement) und erstreckt sich bis zur Entsorgung der zugehörigen Systemkomponenten.

### Management-Tipps

Die Planung organisatorischer Sicherheitsmassnahmen sind typische Managementaufgaben. Grundlage dafür ist ein systematisches ISMS und LCM. Ausserdem gehören aktuelle Sicherheitskonzepte und -Weisungen sowie ein funktionierendes Dokumentationssystem dazu.

## Kapitel 12 - Technische Massnahmen planen und umsetzen

Im Massnahmenkatalog Kommunikation muss die Netzwerkinfrastruktur (Router, Switch, Verkabelung etc.) gegen Sabotage, Zerstörung oder unbefugten Zugriff abgesichert werden. Mithilfe von Intrusion-Detection-Systemen können Angriffe schnell erkannt werden. Die drahtlose Kommunikation ist aufgrund ihrer Zugänglichkeit besonders exponiert und daher speziell zu schützen. Starke Authentifizierungs- und Verschlüsselungsmechanismen sind hier notwendig.

Gebäude und Räume, die schützenswerte Systemkomponenten bzw. Daten beherbergen, müssen ebenfalls gesichert werden. Je nach Situation sind sie mit einer redundanten Stromversorgung, Klimakontrolle oder Überwachung auszustatten. Wichtige Voraussetzungen für sichere Gebäude und Räume sind zudem eine gute Standortwahl sowie eine vollständige, aktuelle Dokumentation. Für die Sicherheit von Gebäuden sind ausserdem Massnahmen im Bereich des Einbruchs- und Perimeterschutzes denkbar bzw. notwendig.

### Management-Tipps

Die Realisierung technischer Sicherheitsmassnahmen setzt entsprechendes Fachwissen voraus. Deshalb ist es in der Praxis nicht die Aufgabe des IT-Sicherheitsbeauftragten, konkrete Massnahmen in diesem Bereich auszuarbeiten und umzusetzen. Er muss aber sicherstellen, dass angemessene Massnahmen ergriffen und nach deren Umsetzung kontrolliert werden. Gerade wenn es um Sicherheitsmassnahmen für Gebäude oder Räume geht, muss der IT-Sicherheitsbeauftragte mit anderen Stellen Zusammenarbeiten und Koordinationsaufgaben wahrnehmen.

## Kapitel 13 - Bereichsübergreifende Massnahmen

Es ist kaum möglich, IT-Sicherheit alleine mit rein technischen, personellen oder organisatorischen Massnahmen sicherzustellen. Für den Datenschutz gibt es relativ klare Bestimmungen für übergreifende Massnahmen. Die Verordnung des Datenschutzgesetzes nennt für folgende Bereiche geeignete Massnahmenbündel:

- Zugangskontrolle
- Datenträgerkontrolle
- Transportkontrolle
- Bekanntgabekontrolle
- Speicherkontrolle
- Benutzerkontrolle
- Zugriffskontrolle
- Eingabekontrolle
- Protokollierung

Data Leaks sind eine der grössten Probleme für ein Unternehmen. Oft entstehen diese von innen, also werden durch interne Mitarbeitende verursacht. Mögliche Lösungen im Rahmen von Data Leak Prevention sind, dass die Speicherung, der gesamte Datenverkehr und die Verwendung der Daten lückenlos überwacht und aufgezeichnet werden.

Bei den Internetdiensten stehen verschiedene Massnahmen im Vordergrund. Einerseits müssen sichere Webserver betrieben werden und der Einsatz von Webbrowsern sicher gemacht werden. E-Mail birgt wegen der notwendigen Offenheit nach wie vor etliche Gefahren in sich. Sicherer Umgang mit E-Mail Adressen und Verteilerlisten helfen unteranderem, E-Mail-Einrichtungen sicher zu betreiben.

Remote-Access-Systeme werden für die sichere Kommunikation mit dem Unternehmens-LAN aus der Ferne verwendet. Durch den Einsatz des Tunneling-Verfahrens kann dies in gewünschter Weise erfolgen.

Firewalls schützen Netzwerke vor Angriffen. Voraussetzung für eine effiziente Abwehr sind entsprechende Filterregeln, wer mit wem wie kommunizieren darf. Packet-Filter sind dabei die meistverwendete Form von Firewalls. Der Erfolgsfaktor für diese Technologien in puncto Sicherheit liegt jedoch immer noch in klaren Einsatzkonzepten, minimalen Betriebssystemen und Diensten sowie in kontrolliertem und strukturiertem Betrieb.

Mobile Speichergeräte umgehen die meisten Sicherheitskonzepte und Sicherheitsmassnahmen. Sie sind schwer zu kontrollieren und können grossen Schaden durch Viren oder Datenverlust erzeugen. Unter diese Kategorie von Speichergeräten fallen USB-Sticks, externe Festplatten und CD/DVD. Diese Speichergeräte müssen besonders überwacht werden und deren Einsatz wo immer möglich verhindert werden. Ist das nicht möglich, so sind Verschlüsselungen die wichtigsten Sicherheitsmassnahmen.

### Management-Tipps

Das Management kümmert sich um die Umsetzungsprojekte und stellt sicher, dass diese gesamtheitlich betrachtet werden. Die Umsetzung der einzelnen Projekte muss überwacht und Probleme müssen frühzeitig erkannt werden. Das Management kommuniziert den Fortgang dieser Projekte und stellt wenn notwendig die richtige Unterstützung zur Verfügung. Gegebenenfalls müssen für problematische Projekte externe Spezialisten hinzugezogen werden.

## Kapitel 14 - Sicherheitsmassnahmen und -aktivitäten überwachen

Im Zusammenhang mit Sicherheitsmassnahmen können generell folgende Monitoringarten
unterschieden werden:

. Reaktive Überprüfung: Wurden die Massnahmen vollständig, korrekt und wirtschaftlich
umgesetzt? Treten in der Praxis Probleme auf (nachträgliche Analyse von Störungen)?
. Proaktive Überwachung: Das Monitoring während des Systembetriebs kann selbst eine
Sicherheitsmassnahme sein (z. B. Zustandsüberwachung eines Webservers).


Das Monitoring von Sicherheitsmassnahmen kann in folgende Phasen und Aktivitäten
gegliedert werden:

- Überwachungsmassnahmen festlegen: Geeignete Monitoringmassnahmen für Systeme und Prozesse müssen festgelegt und mit den notwendigen finanziellen Mitteln ausgestattet werden. Dabei ist insbesondere darauf zu achten, dass die Datenschutz- und Arbeitsgesetze berücksichtigt werden; die Privatsphäre von Mitarbeitenden und Kunden muss unbedingt berücksichtigt werden.
- Überwachungsmassnahmen kontrollieren: Die Monitoringmassnahmen müssen regelmässig kontrolliert werden - typischerweise monatlich oder quartalsweise. Das Management kann auch stichprobenartige Überwachungen anordnen.
- Auswertungen anfordern: Die Ergebnisse der Monitoringmassnahmen werden meist in Form von Reports ausgewertet und managementgerecht (stark konsolidiert) aufbereitet. Im Idealfall werden die Berichte automatisch erzeugt und über ein Management Information System (MIS) bereitgestellt. Ausgebaute Reportingsysteme bieten auch die Möglichkeit, konsolidierte Kennzahlen detailliert zu analysieren. In diesem Zusammenhang ist die Frage der «angemessenen Kennzahl» und der «richtigen Messung» von entscheidender
Bedeutung: in der Praxis werden oft Kennzahlen erhoben und präsentiert, die nicht den objektiven Zustand der IT-Sicherheit widerspiegeln.
- Korrekturmassnahmen initiieren: Aufgrund der Auswertungen werden geeignete Korrekturmassnahmen angeordnet. Dabei ist der Trendentwicklung besondere Beachtung zu schenken.

Wichtig ist, dass die Monitoring-Ergebnisse analysiert, beurteilt und für die Optimierung der
Sicherheitsmassnahmen weiterverwendet werden. Ein Monitoring ohne eine angemessene Reaktion auf die Ergebnisse bringt nur unnötigen Aufwand.

### Management-Tipps

Das unternehmerische ISMS einschliesslich der Sicherheitspolitik und Sicherheitsziele gehört in regelmässigen Abständen punkto Effizienz und Effektivität überprüft werden. Dazu gehört auch die Ermittlung und Beurteilung von Verbesserungsmöglichkeiten. Die Ergebnisse der Überprüfung sind zu dokumentieren. Gegebenenfalls sind auch manuelle Aufzeichnungen anzufertigen.

## Kapitel 15 - Audits und Tests organisieren und durchführen

Wenn Sicherheitsmassnahmen einen Geschäftsprozess massiv behindern, kann auf deren Umsetzung verzichtet werden bzw. können entsprechende Anforderungen oder geltende Regelungen auch umgangen werden. Eine solche «Nicht-Anwendbarkeit» von Massnahmen muss entsprechend dokumentiert und durch den jeweiligen Prozesseigner getragen werden.

### Management-Tipps

Die nachfolgende Liste erläutert, welche Themenbereiche der Sicherheitsverantwortliche bezüglich Review, Audit und Test zu berücksichtigen hat:

- Interne und externe Revision durchführen: Die regelmässige Anordnung, vor allem von internen Revisionen und Audits ist eine wichtige Verantwortung des Managements. Die Durchführung von externen Revisionen ist insbesondere bei Aktiengesellschaften und GmbHs gesetzlich vorgeschrieben. Durch einen Ausbau der internen Revision kann der Aufwand für (die teurere) externe Revision erheblich reduziert werden.
- Sicherheitsaudit durchführen: Technische Security Audits werden durch das Management mit den notwendigen Ressourcen ausgestattet. Oft verfügen Projekte und Linienstellen über ungenügende Mittel, um Sicherheitstests durchzuführen, da diese klassischerweise in den Projektbudgets nicht berücksichtigt werden oder als Erstes den Budgetkürzungen zum Opfer fallen. Ein wichtiger Punkt sind Sicherheitsaudits bei System- und Anwendungsentwicklungen.
- Zertifizierung anstreben: Je nach Branche und Anforderungen seitens Lieferanten und Kunden kann es notwendig sein, eine Zertifizierung der Organisation anzustreben, z.ß. ISO/IEC-27001-Zertifizierung, Grundschutz-Zertifizierung oder ein Datenschutz-Gütesiegel. Eine erfolgreiche Zertifizierung dient auch als Mittel der Kommunikation gegenüber Kunden und dem Markt generell und kann in Zusammenarbeit mit Medienstellen / Public Relations angestrebt werden. Ein weiterer Punkt ist die Beschaffung von Systemen und Produkten. Hier kann angestrebt werden, dass nur entsprechend zertifizierte Produkte beschafft werden, um bereits eine grundlegende Sicherheit durch den Hersteller zu fordern.
- Organisatorische Rahmenbedingungen sicherstellen - im Rahmen eines internen Kontrollsystems: Die organisatorischen Rahmenbedingungen sind durch Schaffung von entsprechenden Stellenprozenten und Rollenbeschreibungen sowie AKV (Aufgaben, Kompetenzen, Verantwortungen) zu schaffen. Die oft auch gesetzlich vorgeschriebenen internen Kontrollsysteme ermöglichen eine weitgehende «Automatisierung» der Kontrollbemühungen, indem entsprechende Vorgaben in die Geschäftsprozesse integriert werden.

## Kapitel 16 - Wirksamkeit und Wirtschaftlichkeit der Massnahmen kontrollieren

Die Wirksamkeit von Sicherheitsprozessen bzw. Sicherheitsmassnahmen kann anhand von Reifegradmodellen bestimmt werden. Dabei wird ermittelt, ob eine Sicherheitsmassnahme die gewünschte Wirkung erzielt (Effektivität) und ob diese Wirkung wirtschaftlich, d. h. mit einem angemessenen Kosten-Nutzen-Verhältnis erreicht wird (Effizienz).

Zur Reifegradmessung der Sicherheitsprozesse werden die zugehörigen Inputs und Outputs geprüft. Für die Beurteilung des Reifegrads des ISMS werden die Ergebnisse des Sicherheitsaudits herangezogen und analysiert. Das wichtigste Maturitätsmodell ist das Capability Maturity Modell (CMM), das fünf Reifegradstufen vorgibt. Weitere Standards für das IT-Sicherheitsmanagement wie z. B. CoblT lehnen sich an diese Reifegradstufen an.

Die Berichterstattung bezüglich der IT-Sicherheit erfolgt über Kennzahlen, die vorgängig zu definieren und zu ermitteln sind. Kennzahlen für die IT-Sicherheit sind zurzeit noch wenig verbreitet. Der IT-Sicherheitsverantwortliche ist daher weitgehend auf sich selbst gestellt, um geeignete Kennzahlen zu finden und bei der Kontrolle der Wirksamkeit und Wirtschaftlichkeit von Sicherheitsmassnahmen heranzuziehen.

### Management-Tipps

Der Sicherheitsverantwortliche muss im Rahmen der Wirksamkeits- und Wirtschaftlichkeitsüberprüfung folgende Verfahren kennen und anwenden können:

- Verfahren festlegen: Aus den verschiedenen Verfahren zur Effizienzmessung sind die geeigneten auszuwählen und als Standard für das Unternehmen festzulegen.
- Kennzahlensystem festlegen: Die Zielgrössen für Maturitätskennzahlen in den verschiedenen Organisationseinheiten sind durch das Management vorzugeben. Wichtig sind insbesondere finanzielle Kennzahlen, um die Investitionen im Bereich der IT-Sicherheit gegenüber der Geschäftsleitung zu rechtfertigen.

## Kapitel 17 - Prüf- und Messergebnisse auswerten und dokumentieren

Die Prüfergebnisse sind systematisch zu dokumentieren, da diese für den Nachweis der durchgeführten Prüfungen wichtig sind. Entsprechende Vorgaben sind festzulegen. Bei der Analyse der Vorfälle in Systemprotokollen fallen enorme Datenmengen an, die manuell nicht zu bewältigen sind. Entsprechend ist auf geeignete Werkzeuge zurückzugreifen, um die Daten systematisch zu analysieren und automatisch zu konsolidieren. Die Prüfergebnisse können dem IT-Sicherheitsbeauftragten und der Unternehmensleitung in einem Security Cockpit verfügbar gemacht werden. Dabei ist besonderes Augenmerk auf die Überwachung der Mitarbeitenden und deren Aktivitäten auf den ICT-Systemen zu richten. Weil hier personenbezogene Daten erhoben und ausgewertet werden, ist darauf zu achten, dass die gesetzlichen Bestimmungen aus den Arbeits- und Datenschutzgesetzen nicht verletzt werden.

### Management-Tipps

Die Anforderungen an das Dokumentenmanagement müssen klar und eindeutig definiert werden. So sind insbesondere die Aufbewahrungsdauer der Dokumente sowie die Formen und Auswirkungen der Klassifikation eines Dokuments vorzugeben.

## Kapitel 18 - Optimierungsmöglichkeiten ermitteln

Die Effizienz und Effektivität des ISMS kann kontinuierlich optimiert werden, indem die Sicherheitskonzepte, Sicherheitsziele und Auditresultate regelmässig überprüft Präventiv- und Korrekturmassnahmen gezielt überwacht und die eingetretenen Risiken bzw. Störungen detailliert analysiert werden.

Bei der Umsetzung von Optimierungsmassnahmen sind oft Mängel festzustellen. Ein Grund dafür sind die fehlenden gesetzlichen Anforderungen bezüglich einer «Optimierung», Zudem steigen die Optimierungskosten für Prozesse mit hoher Maturität überproportional an, während sich der sichtbare Nutzen der Optimierung in Grenzen hält. In der Praxis ist es daher wichtig, einen bestimmten Pragmatismus walten zu lassen.

### Management-Tipps

IT-Sicherheit kann durch korrigierende und präventive Massnahmen gezielt optimiert werden. Vor jedem Eingriff müssen aber die Auswirkungen der Korrektur- und Präventivmassnahmen analysiert und die geplanten Verbesserungsmassnahmen aufeinander abgestimmt werden. In manchen Fällen kann es auch notwendig sein, bestimmte Massnahmen komplett zu ersetzen oder wegzulassen. Das primäre Ziel der korrigierenden Massnahmen sollte darin bestehen, Bedrohungen durch neue Risiken zu vermeiden.

## Kapitel 19 - Verbesserungsmassnahmen planen und umsetzen, Sicherheitskultur fördern

Risikokommunikation hat einen hohen Stellenwert im Optimierungsprozess, da eine transparente und zeitnahe Kommunikation der Risiko- und Massnahmensituation einerseits zeigt, dass man die Risiken «im Griff hat», und andererseits das Vertrauen von Mitarbeitenden, Kunden und der Öffentlichkeit entsprechend geprägt werden kann. In der Praxis wird oft vermieden über Risiken zu kommunizieren, da dies oft negativ konnotiert wird. Aus Angst wer den so Risiken nicht oder mangelhaft kommuniziert. Die Auswirkungen auf den Markennamen bei verfehlter Risikokommunikationspolitik sind nicht zu unterschätzen.

Ein weiterer Schwachpunkt stellt die Sicherheit in der Systementwicklung dar. Sicherheitsanforderungen werden in Entwicklungsprojekten oft zu spät oder gar nicht berücksichtigt, weil sie anfänglich nicht budgetiert werden oder eine rasche Umsetzung der funktionalen Anforderungen behindern. Verschiedene grosse Unternehmen haben inzwischen Prozesse etabliert, um die Sicherheitsanforderungen von Anfang an zu berücksichtigen.

### Management-Tipps

Zur Förderung des Sicherheitsbewusstseins sind folgende Aspekte zu beachten:

- Risikokommunikation: Ein zunehmend wichtiger Aspekt ist die Kommunikation der aktuellen Risiken und der geplanten und ergriffenen Gegenmassnahmen. In der Praxis wird oft vermieden, von Risiken zu sprechen, oder die Realität wird schöngeredet. Aufgrund der heutigen Vernetzung ist es für Mitarbeitende, Kunden und die Öffentlichkeit aber nicht mehr so aufwendig, die effektive Risikosituation zu ermitteln. Entsprechend muss das Management reagieren und proaktiv eine geeignete Risikokommunikation umsetzen.
- Umgang mit Veränderungen: Veränderungen stellen für die betroffenen Mitarbeitenden einen Eingriff in die «gelebten» Prozesse dar. Aus diesem Grund müssen kritische Stimmen ernst genommen werden und das Management muss darauf angemessen reagieren. Dabei ist insbesondere darauf zu achten, dass es nicht zu einer Endlosschlaufe der Kritik kommt und die Optimierung der IT-Sicherheit letztlich auf der Strecke bleibt.

## Kapitel 20 - Strategie, Konzepte, Notfallpläne, ISMS und Massnahmen anpassen

Die Sicherheitsstrategie sollte mindestens alle drei bis fünf Jahre mit den Vorgaben aus der IT-Strategie und Unternehmensstrategie abgeglichen und angepasst werden.

Die Sicherheitskonzepte für den operativen Bereich und aus Projekten haben einen Anpassungs- und Review-Zyklus von ein bis drei Jahren, je nach Lebenszyklus der zugrunde liegenden Anwendungen und Systeme.

Die Anpassung der Notfallpläne wird in der Praxis oft vernachlässigt. Neben dem wichtigen Testen und Üben von Notfallplänen ist die umgehende Anpassung aufgrund der Testresultate unabdingbar. Auch Verteilerlisten und Eskalationspläne müssen fortlaufend an die aktuelle Situation angepasst werden, damit im Notfall alle wichtigen Informationen zeitgerecht an der richtigen Stelle zur Verfügung stehen.

### Management-Tipps

Der IT-Sicherheitsbeauftragte muss bezüglich der Anpassung des ISMS folgende Aspekte berücksichtigen:

- Sicherheitsstrategie, Sicherheitskonzepte und Notfallpläne sind regelmässig zu reviewen.
- Es sind angemessene Anpassungsfristen zu wählen; keine allzu lange Fristen setzen, da die Anpassung oft nicht zum festgelegten Zeitpunkt, sondern später vorgenommen wird.
- Notfallpläne müssen stets topaktuell sein. Notfallübungen sind ziemlich aufwendig und werden deshalb von vielen Unternehmen gescheut.

## Kapitel 21 - Kontinuierliche Qualitätsverbesserung

Der Kontinuierliche Verbesserungsprozess (KVP) setzt folgende Grundeinstellung bei der Planung, Umsetzung und Überprüfung von Prozessen und Massnahmen voraus: Jede sich bietende Gelegenheit zur Verbesserung soll genutzt werden, um eine nachhaltige Optimierung zu gewährleisten. Zu diesem Zweck gibt es verschiedene Ansätze, die vor allem im industriellen Produktionsbereich erfolgreich umgesetzt werden. Deren Anwendung im Dienstleistungssektor erfolgt seit einigen Jahren ebenfalls mit hoher Akzeptanz durch die betroffenen Mitarbeitenden. Diese haben dadurch die Gelegenheit, die theoretischen Zielvorgaben mit den Gegebenheiten aus der Praxis abzugleichen, um so eine optimale Zielerreichung zu ermöglichen. Die verschiedenen Methoden für KVP sind:

- Kaizen, aus der japanischen Industrie
- Total Quality Management (TQM), in Europa etabliert
- Six Sigma aus der industriellen Fertigung

### Management-Tipps

Für die kontinuierliche Verbesserung der IT-Sicherheitsprozesse sind für den Sicherheitsverantwortlichen besonders die folgenden Punkte von Bedeutung:

- KVP einführen und managen: Es soll eine Kultur zum Thema der kontinuierlichen Verbesserung im Unternehmen eingeführt werden, was zu einer entsprechend notwendigen Einstellung der Mitarbeitenden führt.
- Qualitätsmanagementsystem implementieren: Qualitätsanforderungen zusammen mit den betroffenen Stellen und den Dienstleistungsbezügern ermitteln und als entsprechende Qualitätsziele formulieren und vorgeben.
- Qualitätsstandards vorgeben: Die Vorgabe der Qualitätsstandards ist nicht zu verwechseln mit der Einhaltung von bestimmten Qualitätssicherungsprozessen. In der Praxis wird oft die ISO/IEC-9001-Zertifizierung als Garant für «gute Qualität» aufgefasst. Tatsächlich bedeutet die Zertifizierung jedoch lediglich, dass die Prozesse zur Erreichung der vorgegebenen Qualitätsziele eingehalten werden. Die Festlegung ebendieser Qualitätsziele ist somit Sache des Managements.

# Fragen

1. Beschrieben sie in einem Satz, wie die Höhe eines Sicherheitsrisikos bewertet werden kann?

- Die Höhe eines Sicherheitsrisikos berechnet sich aus dem bewerteten Schaden pro Ereignisfall (CHF) multipliziert mit der Eintrittswahrscheinlichkeit (%).

2. Nennen sie die vier Schutzziele der Datensicherheit und beschrieben sie diese Stichwortartig.

- Die vier Schutzziele der Datensicherheit lauten:
    - Vertraulichkeit: Schutz vor Einsicht durch Dritte
    - Integrität: Richtigkeit der Daten
    - Verfügbarkeit: Wartezeit auf eine Systemfunktion
    - Verbindlichkeit: Nachweis eines Geschäftsvorfalls

3. Welche drei Aspekte umfasst das Schutzziel Integrität? Beschrieben sie diese Aspekte stichwortartig.

- Im Zusammenhang mit Daten und Informationen umfasst der Begriff «Integrität» folgende Aspekte:
    - Realität: Integere Daten bzw. Informationen entsprechen der Realität.
    - Aktualität: Integere Daten bzw. Informationen sind aktuell.
    - Authentizität: Integere Daten bzw. Informationen kommen von einer vertrauenswürdigen Quelle bzw. Person.

4. Im Vertielerraum eines Rechenzentrums ist ein Brand ausgebrochen. Systembetrieb konnte auf ein anderes System umgeschaltet werden ohne Unterbruch. Netzwerkverkabelung ist zerstört. Nennen sie drei Schadenskathegorien und beurteilen sie, welche Schäden hier vorliegen.

- Direkter Schaden: Netzwerkkabel und zugehörige Infrastruktur
- Indirekter Schaden: alte Verkabelung entfernen, neue Verkabelung installieren. Systembetrieb auf das ursprüngliche Rechenzentrum umschalten
- Folgekosten: keine, da kein Daten- oder Produktionsverlust entstanden ist

5. Nennen sie drei Aspekte des Governance-Prinzips und ennen sie für jeden Aspekt eine entsprechende Anforderung an die Informatik.

- Unter dem Governance-Prinzip wird die Beherrschbarkeit, Steuerung und Überwachung einer Organisation oder von Organisationseinheiten verstanden.
    - Beherrschbarkeit: Für die Bewältigung der IT-Aufgaben müssen geeignete Verfahren und Methoden angewendet werden (z. B. Testmethoden).
    - Steuerung: Die IT-Organisation muss über klare Aufträge, Weisungen und Richtlinien verfügen.
    - Überwachung: Die IT-Prozesse werden systematisch kontrolliert und bei Störungen oder Problemen werden geeignete Massnahmen eingeleitet.

6. Nennen Sie mindestens fünf Kategorien von Daten bzw. Informationen über natürliche Personen, die unter das DSG fallen.

- Folgende Datenkategorien natürlicher Personen gelten gemäss DSG als besonders schützenswert:
    - Religiöse Ansichten oder Tätigkeiten
    - Weltanschauliche Ansichten oder Tätigkeiten
    - Politische Ansichten oder Tätigkeiten
    - Gewerkschaftliche Ansichten oder Tätigkeiten
    - Gesundheit
    - Intimsphäre
    - Ethnische Zugehörigkeit
    - Soziale Unterstützungsmassnahmen
    - Informationen über administrative oder strafrechtliche Massnahmen

7. Welche Punkte mit Bezug zur IT-Sicherheit regelt das OR? Beschreiben Sie mindestens zwei Aspekte.

- Das OR regelt u.a. folgende Punkte, die sich auf die IT-Sicherheit auswirken:
    - Verschwiegenheit und Berufsgeheimnis: Arbeitnehmer dürfen gegenüber Dritten keine Informationen über ihre Tätigkeiten für den Arbeitgeber herausgeben (z. ß. über Kundenbeziehungen). Um das Geschäfts- und Berufsgeheimnis zu wahren, können IT-Sicherheitsmassnahmen notwendig sein.
    - Aufsicht und Kontrolle: In einer Aktiengesellschaft ist der Verwaltungsrat zur Oberaufsicht und Kontrolle verpflichtet. Er muss dafür sorgen, dass die Geschäftsaktivitäten und -bücher korrekt und wahrheitsgemäss geführt werden. Mithilfe von IT-Sicherheitsmassnahmen kann diese Anforderung gewährleistet werden.
    - Sorgfaltspflicht: Geschäftsbücher sind sorgfältig zu führen und aufzubewahren. Dasselbe gilt auch für alle Geschäftsbücher bzw. -unterlagen, die in elektronischer Form vorliegen. Sicherheitsmassnahmen im Bereich der Archivierung elektronischer Informationen tragen dieser Anforderung Rechnung.

8. Nennen Sie drei Delikte mit Bezug zur IT-Sicherheit, die durch das StGB geahndet werden.

- Folgende Delikte, die die IT-Sicherheit betreffen, werden durch das StGB geahndet:
    - Unbefugte Datenbeschaffung
    - Hacking in fremde Systeme
    - Verletzung der Datenintegrität
    - Unrechtmässige Bereicherung

9. Welche drei Anforderungen sind bei der Archivierung von Geschäftsdaten gemäss GebüV zu beachten?

- Grundsätzlich gilt, dass Geschäftsdaten so aufzubewahren sind, dass folgende Anforderungen erfüllt werden:
    - Echtheit und Unverfälschbarkeit
    - Sorgfaltspflicht
    - Verfügbarkeit und Zugänglichkeit
    - Datenträger, die es erlauben, eine Veränderung der Daten nachzuvollziehen

10. Welcher Standard bietet ein umfassendes Rahmenwerk für die IT-Governance und in welche Domänen werden die IT-Prozesse dabei gegliedert?

- CoblT ist ein anerkanntes Rahmenwerk für die Beherrschung bzw. Steuerung der gesamten Informatik in einem Unternehmen. In diesem Standard werden die IT-Prozesse in folgende Domänen unterteilt:
    - Planung und Organisation (Plan and Organise)
    - Beschaffung und Implementation (Acquire and Implement)
    - Auslieferung und Unterstützung (Deliver and Support)
    - Überwachung und Optimierung (Monitor and Evaluate)

11. Wofür steht die Abkürzung OSSTMM und was wird in diesem Standard beschrieben? Antworten Sie in einem Satz.

- OSSTMM steht für Open Source Security Testing Methodology Manual und beschreibt eine Methode für die Planung, Durchführung und Dokumentation technischer Sicherheitsaudits.

12. Woher stammen externe Anforderungen an die IT-Sicherheit? Nennen Sie vier wichtige Anspruchsgruppen.

- Externe Sicherheitsanforderungen werden hauptsächlich vom Gesetzgeber und von Branchenverbänden formuliert bzw. von Gesetzen, Normen und Standards abgeleitet. Daneben tragen Kunden und Lieferanten externe Anforderungen bezüglich der IT-Sicherheit an ein Unternehmen heran.

13. Woher stammen interne Anforderungen an die IT-Sicherheit? Nennen Sie vier wichtige Anspruchsgruppen.

- Interne Sicherheitsanforderungen werden hauptsächlich aus der Unternehmens- und Risikostrategie abgeleitet. Sie stammen i.d. R. aus dem Qualitäts- und Risikomanagement, aus der Informatikabteilung und von den Systembenutzern.

14. Wie und wozu sollten die erhobenen Anforderungen festgehalten werden? Antworten Sie möglichst knapp.

- Die erhobenen Anforderungen lassen sich mithilfe eines Anforderungskatalogs schriftlich festhalten und übersichtlich darstellen. Der Anforderungskatalog kann später auch als Grundlage für die Beurteilung der Risiken und des angestrebten Sicherheitsniveaus herangezogen werden.

15. Beschreiben Sie in einem Satz die Hauptaufgabe von IT-Sicherheitsbeauftragten und nennen Sie mindestens fünf operative Einzelaufgaben.

- Die Hauptaufgabe von IT-Sicherheitsbeauftragten besteht darin, die Geschäftsleitung bei der Erfüllung der Sicherheitsanforderungen zu beraten und bei der Umsetzung zu unterstützen.

- Dazu gehören i.d.R. folgende operativen Einzelaufgaben:
    - Geschäftsleitung bei der Definition und Umsetzung der Sicherheitspolitik unterstützen
    - Geschäftsleitung bei der Definition und Umsetzung der Sicherheitsstrategie unterstützen
    - Sicherheitskonzept erstellen
    - Notfallvorsorge planen und organisieren
    - Sicherheitsstrukturen und -prozesse etablieren und anpassen
    - Richtlinien und Anweisungen zur IT-Sicherheit erlassen und koordinieren
    - Sicherheitsmassnahmen initiieren und überprüfen
    - Geschäftsleitung regelmässig über den Status und die Veränderungen im Sicherheitsbereich orientieren
    - Sicherheitsrelevante Projekte begleiten und koordinieren
    - Sicherheitsvorfälle untersuchen und ggf. Verbesserungsmassnahmen einleiten
    - Sensibilisierungs- und Schulungsmassnahmen zur IT-Sicherheit initiieren und koordinieren

16. Warum braucht es in grossen Unternehmen neben dem IT-Sicherheitsbeauftragten zusätzlich Risikoverantwortliche in den Fachabteilungen? Antworten Sie möglichst knapp.

- Ein IT-Sicherheitsbeauftragter ist nicht immer in der Lage, alle Risiken richtig einzuschätzen und die Angemessenheit der Sicherheitsmassnahmen korrekt zu beurteilen. Zumindest in grossen Unternehmen ist er in dieser Hinsicht auf die Unterstützung von Spezialisten aus den Fachabteilungen angewiesen. Gemäss dem Grundsatz «Übereinstimmung von Verantwortung, Aufgaben und Kompetenzen» wird die Verantwortung für Risiken den Fachabteilungen übertragen. Dies bedeutet, dass für jedes Risiko ein Verantwortlicher mit entsprechenden Fachkompetenzen bestimmt wird.

17. Auf welcher Grundlage werden Risiken behandelt und welche Bewältigungsstrategie lassen sich unterscheiden?

- Die Risiken werden gemäss der Risikostrategie behandelt. Dabei können folgende Bewältigungsstrategien unterschieden werden:
    - Risikoeliminierung: Hier werden die Ursachen der Risiken vollständig behoben, d.h. die Risiken können nicht mehr (in dieser Form) auftreten. Diese Strategie ist häufig die teuerste.
    - Risikominimierung: Hier werden Vorkehrungen getroffen, um die Risiken auf ein bestimmtes Niveau bzw. auf das akzeptierte Schadenpotenzial zu reduzieren. Diese Strategie wird häufig bei Risiken angewendet, die sich nicht eliminieren lassen.
    - Risikotransfer: Hier werden die Risiken ausgelagert bzw. an Dritte übertragen (z.B. an eine Versicherung). Diese Strategie wird häufig bei Risiken angewendet, die sich nicht genügend minimieren lassen.
    - Risikoakzeptanz: Hier werden (Rest)Risiken bewusst in Kauf genommen. Diese Strategie wird häufig bei Risiken angewandt, die sich weder eliminieren noch minimieren oder transferieren lassen. Das Gegenteil der Risikoakzeptanz ist die Risikonegierung nach dem Motto “Uns kann das nicht passieren”

18. Welche Methoden stehen für die Identifikation von Risiken zur Verfügung? Nennen sie für jede Methode drei zugehörige Techniken.

- Für die Identifikation von Risiken stehen grundsätzlich folgende Methoden zur Verfügung:
    - Kollektionsmethoden: Checkliste, Befragung, Beobachtung, Interview, Self-Assessment:
    - Analytische Suchmethoden: Prozessanalyse, Fehlermöglichkeits- und Einflussanalyse (FMEA), Angriffsbäume, Hazard and Operability (HAZOP), Recherche
    - Kreativitätsmethoden: Brainstorming, Brainwriting (Mindmapping), Synektik, Delphi-Methode

19. Welche Darstellungsform eignet sich, um voneinander abhängige Risiken aufzuzeigen?

- Die Risikomatrix

20. Welche Aspekte sind bei der Auswahl des Risikobewertungsverfahren zu berücksichtigen?

- Bei der Auswahl eines Risikobewertungsverfahrens sind folgende Aspekte zu berücksichtigen:
    - Benötigter Detaillierungsgrad bei der Berechnung des Schadenpotenzials
    - Komplexität der zu bewertenden Prozesse
    - Verfügbarkeit der Prozesse und Informationen
    - Kosten für die Durchführung der Bewertungsverfahren
    - Know-how der mit der Aufgabe betrauten Mitarbeitenden

21. Nennen sie zwei wesentliche Nachteile von quantitativen Bewertungsverfahren.

- Bei komplexen Untersuchungsbereichen sind quantitative Bewertungsverfahren mit grossem Aufwand verbunden. Müsste z. B. das Gesamtrisiko für sämtliche Aufgaben und Prozesse einer IT-Abteilung quantitativ «gemessen» werden, so kann der dafür anfallende Aufwand mögliche Einsparungen durch Risikoverhinderung bei Weitem übersteigen. Zudem fehlen meist verlässliche Erfahrungswerte für die Eintrittswahrscheinlichkeit und für das (maximale) Schadenausmass.

22. Welche Fragen sollen im Rahmen der Business-Impact-Analyse beantwortet werden?

- Im Rahmen der Business-Impact-Analyse sollen folgende Fragen beantwortet werden:
    - Welches sind die vorrangigen Ziele des Unternehmens?
    - Welche Prozesse, Dienste, Anwendungen oder Funktionen dürfen maximal wie lange ausfallen?
    - In welchem Zeitraum muss eine Störung bzw. eine ungeplante Unterbrechung behoben werden?
    - Welche Ressourcen werden benötigt, um ausgefallene Prozesse, Dienste, Anwendungen oder Funktionen wiederherzustellen?
    - Welche internen und externen Abhängigkeiten sind bei der Umsetzung der Prioritäten zu berücksichtigen?

23. Charakterisiere die Unternhemensstrategie anhand von drei Eigenschaften.

- Eine Unternehmensstrategie zeichnet sich durch folgende Eigenschaften aus:
  - Sie zeigt die mittel- bis langfristige Entwicklung der Geschäftsprozesse im Unternehmen auf.
    - Sie orientiert sich an den Zukunftschancen auf dem Markt.
    - Sie orientiert sich an den zu erwartenden Geschäftsrisiken.
    - Sie hat eine hohe Kapitalbindung (für Investitionen) zur Folge.
    - Sie gibt eine Richtung vor, die kurzfristig nur schwer geändert bzw. korrigiert werden kann.
    - Sie beeinflusst alle anderen Strategien des Unternehmens.

24. Woraus wird die IT-Strategie abgeleitet und was zeigt sie generell auf? Antworten Sie in einem Satz.

- Die IT-Strategie wird aus der Unternehmensstrategie abgeleitet und zeigt den Weg auf, wie die Informations- und Kommunikationstechnologien zugunsten des Unternehmenserfolgs einzusetzen sind.

25. Welche Elemente sollten eine brauchbare IT-Sicherheitsstrategie beinhalten?

- Eine brauchbare IT-Sicherheitsstrategie sollte folgende Elemente beinhalten:
    - Sicherheitsdefinition
    - Commitment der Geschäftsleitung
    - Anwendungsbereich
    - Sicherheitsorganisation
    - Sicherheits- und Schutzziele
    - Sicherheitskontrolle

26. Beschreiben Sie möglichst knapp den Zweck und die Inhalte eines IT-Sicherheitskonzepts.

- Das IT-Sicherheitskonzept zeigt auf, wie ein Unternehmen die Vorgaben der IT-Sicherheitsstrategie umsetzen will. Hier wird beschrieben, welche Risiken mit welchen Massnahmen bekämpft werden und welche organisatorischen Rahmenbedingungen gelten. Es ist sozusagen das «Kochbuch» der IT-Sicherheitsbeauftragten für die Erfüllung der Sicherheitsanforderungen.

27. Wozu wird im Zusammenhang mit dem IT-Sicherheitskonzept ein Kontrollmodell benötigt? Antworten Sie möglichst knapp.

- Anhand des Kontrollmodells kann die Vollständigkeit des IT-Sicherheitskonzepts überprüft werden. Dabei sollen folgende Fragen beantwortet werden:
    - Werden alle Sicherheitskriterien berücksichtigt?
    - Werden alle internen und externen Sicherheitsanforderungen abgedeckt?
    - Werden die relevanten Standards und Best Practices gewürdigt?

28. Welche sieben Schritte werden bei der allgemeinen Risikoanalyse durchlaufen?

- Vorgehensschritte im Rahmen einer allgemeinen Risikoanalyse:
    - Risikoanalyse initiieren
    - System abgrenzen
    - Datenbestände identifizieren
    - Verletzbarkeiten identifizieren
    - Bedrohungen identifizieren
    - Risiken identifizieren
    - Risiken bewerten

29. Wie kann die Verletzbarkeit von Datenbeständen ermittelt werden? 1 Satz

- Die Verletzbarkeit von Datenbeständen kann aufgedeckt werden, indem sie den Schutzzielen Vertraulichkeit, Verfügbarkeit, Integrität und Verbindlichkeit gegenübergestellt und danach beurteilt werden.

30. Wie kann ein Risiko anhand der Verletzlichkeit und Bedrohung definiert werden? 1 Satz

- Ein Risiko besteht überall dort, wo eine Verletzbarkeit auf eine Bedrohung trifft.

31. Im Rahmen der Business-Impact-Analyse werden Szenarien aufgestellt und Fragen formuliert, die eine Identifekation der Sicherheitsrisiken erleichtern sollen. Stellen sie vier Fragen, die in diesen Zusammenhang interessieren.

- Zu jedem Szenario werden folgende Fragen gestellt:
    - Was kann alles passieren, wenn dieses Szenario eintrifft?
    - Wie können die schlimmsten Auswirkungen mit dem geringsten Aufwand verhindert werden?
    - Welche Auswirkungen hat das Szenario für das Unternehmen kurz-, mittel- und langfristig?
    - Welche Sicherheitsvorkehrungen sind notwendig, damit der Geschäftsprozess diesem Szenario standhalten kann?

32. Wozu wird bei der Strukturanalyse eine Gruppenbildung vorgenommen? Nennen sie ein Beispiel für Gruppenbildung.

- Durch Gruppenbildung kann die Komplexität des untersuchten Systems reduziert und einzelne Systemkomponenten in eine überschaubare Anzahl von Gruppen gegliedert werden.
  - Beispiel: Zusammenfassung mehrerer Clientcomputer zu Standardarbeitsplätzen

33. Wie können im Rahmen von CobIT Sicherheitslücken aufgedeckt werden und welche beiden Kriterien werden zur Beurteilung der Risiken herangezogen.

- Bestehende Sicherheitslücken können mittels CRSA-Formular selbstständig aufgedeckt werden. Für die Beurteilung der Risiken werden die Bedeutung und der Erfüllungsgrad der IT-Prozesse als entscheidende Kriterien herangezogen.

34. Nennen sie zwei Ereignisse, die beim IT-Sicherheitsprozess bewirtschaftet werden.

- Im Rahmen des IT-Sicherheitsprozesses werden folgende Ergebnisse bewirtschaftet:
    - IT-Sicherheitskonzept
    - IT-Sicherheitsweisungen und -richtlinien

35. Fassen sie den inhalt und nutzen einer sicherheitsleitlinie in ein bis zwei Sätzen zusammen.

- Eine IT-SIcherheitsleitlinie enthält das Bekenntnis des Managements sowie die wichtigsten Grundsätze des Unternehmnens in Bezug auf die IT-Sicherheit. Sie kann als Ausgangslage oder als Auftrag für das ISMS herangezogen werden

36. Führen sie vier Situationen auf, in denen ein Eskalationsplan zum Einsatz kommen kann.

- Ein Eskalationsplan kann in folgenden Situationen zum Einsatz kommen:
    - Bei der Bearbeitung von Vorfällen im Rahmen des Incident Managements
    - Bei der Bearbeitung von Problemen im Rahmen des Problem Managements
    - Bei der Bearbeitung von Sicherheitsvorfällen im Rahmen des Security Managements
    - Beim Auftreten geschäftskritischer Ereignisse in einer Fachabteilung
    - Beim Auftreten geschäftskritischer Ereignisse während des Systembetriebs

37. In welche vier Phasen lässt sich der IT-Sicherheitsprozess generell gliedern? Charakterisieren sie die einzelnen phasen stichwortartig.

- Der IT-Sicherheitsprozess lässt sich generell in folgende Phasen gliedern:
    - Plan: Aktivitäten planen
    - Do: nach Plan handeln
    - Check: überprüfen, ob die Ziele erreicht werden konnten
    - Act: Änderungen, Verbesserungen einleiten

38. Nennen sie drei Ressourcen, die für ein ISMS von zentraler Bedeutung sind.

- Folgende Ressourcen sind für ein ISMS von zentraler Bedeutung:
    - Zeitliche Kapazitäten der Personen, die massgeblich am ISMS beteiligt sind
    - Finanzielle Mittel für die notwendigen IT-Sicherheitsmassnahmen
    - Mittel für einen stabilen Systembetrieb (IT-Infrastruktur, Mitarbeitende für das Monitoring und Testing der ICT-Systeme)

39. Welche drei Elemente umfasset ein Baustein aus dem IT-Grundgesetz und worin besteht der Nutzen der einzelnen Elemente? Fassen sie sich möglichst kurz.

- Ein IT-Grundschutzbaustein umfasst folgende Elemente:
    - Beschreibung des Bausteins und seines Geltungsbereichs: Dadurch ist bekannt, wo und wofür dieser Baustein eingesetzt werden kann.
    - Bedrohungskatalog für den Betrachtungsbereich: Dadurch können für den jeweiligen Betrachtungsbereich die potenziellen Risiken abgeleitet werden.
    - Massnahmenkatalog für ein mittleres Schutzniveau: Dadurch können für den jeweiligen Betrachtungsbereich die umzusetzenden Sicherheitsmassnahmen abgeleitet werden.

40. Begründen sie möglichst knapp, warum die Massnahmen beim IT-Grundschutz in Bausteine gegliedert werden.

- Die Gliederung in Bausteine ergibt einen Modulbaukasten, aus dem ein Unternehmen je nach Situation (IT-Infra Struktur, IT-Organisation) und Bedarf (Sicherheitsanforderungen) den oder die benötigten Baustein(e) auswählen und die entsprechenden Massnahmen umsetzen kann. Die Modularisierung erlaubt zudem eine Aktualisierung und Erweiterung bzw. Reduktion der bestehenden Module.

41. Beschreiben sie drei Bereiche, die unter den Punkt "Einhaltung gesetzlicher und normativer Verpflichtungen" des Standards ISO/IEC 17799 fallen.

- Folgende Bereiche fallen unter diesen Punkt:
    - Einhaltung der Lizenzbestimmungen: Alle Softwarekomponenten, die im Unternehmen eingesetzt werden, müssen ordnungsgemäss lizenziert werden.
    - Einhaltung der vertraglichen Verpflichtungen: Die vertraglichen Verpflichtungen müssen bekannt sein sowie eingehalten und bewirtschaftet werden.
    - Ordentliches Rechnungswesen: Das Rechnungswesen und die Buchhaltung müssen den gesetzlichen Bestimmungen entsprechen.

42. Nennen sie drei mögliche Szenarien für ein Notfallkonzept.

- Beispielszenarien für Notfallkonzepte:
    - Totalausfall des Rechenzentrums
    - Unbenutzbare Büroräume
    - Angriff über das Internet

43. Vor der Erstellung eines Notfallkonzepts müssen ggf. bestimmte Vorarbeiten geleistet werden. Nennen und begründen Sie drei mögliche Massnahmen jeweils in einem Satz

- Mögliche Massnahmen, die im Vorfeld eines Notfallkonzepts ergriffen werden müssen:
    - Datensicherungskonzept erstellen, um im Notfall den ursprünglichen Zustand der Daten wiederherzustellen.
    - Redundante Infrastrukturkomponenten auf bauen, um im Notfall einen kontinuierlichen System betrieb zu gewährleisten.
    - Wartungs- und Reparaturverträge abschliessen bzw. prüfen und ggf. aktualisieren, um ausgefallene Dienste oder Komponenten im Notfall schnell zu reparieren oder zu ersetzen.

44. Ein Unternehmen hat das Risiko "Falscheingabe in ein System" identifiziert. Nennen sie eine vorbeugende, eine aufdeckende und eine lenkende Sicherheitsmassnahme und bescheiben sie deren Wirkung jeweils in einem Satz.

- Mögliche Sicherheitsmassnahmen für das Risiko «Falscheingabe in ein System»:
    - Vorbeugende Massnahme: Eine Plausibilisierung der Systemeingaben kann verhindern, dass Falscheingaben gemacht werden.
    - Aufdeckende Massnahme: Logeinträge bei Fehlermeldungen, die durch die Verarbeitung falscher Eingaben entstehen, werden zentral gesammelt und ausgewertet.
    - Lenkende Massnahme: Gezielte Schulung der Mitarbeitenden, die mit dem betreffenden System arbeiten und Daten erfassen.

45. Ein Unternehmen hat beschlossen, ein neues Zutrittskonzept für die Gebäude und Räume mit IT-Infrastruktur umzusetzen. Wer sollte für die Umsetzung dieses Konzepts verantwortlich gemacht werden und warum?

- Die Verantwortung für die Umsetzung des neuen Zutrittskonzepts sollte beim Leiter der Abteilung Infrastruktur (und nicht beim IT-Leiter) liegen. Begründung: Es braucht eine neutrale und zentrale Instanz, die für alle Gebäude und Räume des Unternehmens zuständig ist, weil ggf. nicht nur die Mitarbeitenden der IT-Abteilung, sondern auch Mitarbeitende anderer Fachabteilungen Zutritt haben müssen.

46. Nennen sie drei potenzielle Sicherheitsrisiken für Desktopsysteme und zeigen sie auf, wie diese durch ein Zugriffskonzept beeiflusst werden können. Antworten sie möglichst knapp.

- Folgende Risiken können im Rahmen eines Zugriffskonzepts beeinflusst werden:
    - Unerlaubte Dateneinsicht und -manipulationen: Der Datenzugriff durch unbefugte Dritte wird durch entsprechende Sicherheitshürden erschwert.
    - Falscheingaben: Nur geschulte und autorisierte Mitarbeitende dürfen Daten erfassen.
    - Fehlmanipulationen: Nur geschulte und autorisierte Mitarbeitende dürfen Daten verändern oder löschen.

47. Wieso müssen personelle Sicherheitsmassnahmen stufengerecht umgesetzt werden? Antworten sie möglichst knapp.

- Jeder Stufe der Aufbauorganisation sind bestimmte Kompetenzen, Aufgaben und Verantwortlichkeiten zugeordnet. Dies gilt auch für die IT-Sicherheit. Daher muss jede personelle Massnahme für die entsprechende Stufe ausgelegt werden. Dies gilt insbesondere für die Schulung der Mitarbeitenden einer bestimmten Hierarchiestufe.

48. Führen sie mindestens drei Gründe auf, warum Security Awareness integrativer Bestandteil von Sicherheitsprogrammen uns Realisierungsplänen sein sollte.

- Security Awareness sollte aus folgenden Gründen integrativer Bestandteil von Sicherheitsprogrammen und Realisierungsplänen sein:
    - Verständnis für Sicherheitsmassnahmen fördern: Jeder betroffene Mitarbeiter soll verstehen, warum bestimmte Sicherheitsmassnahmen ergriffen wurden und wie er korrekt damit umgeht.
    - Regulären Systembetrieb aufrechterhalten: Jeder betroffene Mitarbeiter sollte die Sicherheitsgefahren kennen, die mit seiner Arbeit verbunden sind, und korrekt mit den damit verbundenen Risiken umgehen.
    - Abweichungen vom regulären Systembetrieb erkennen: Jeder betroffene Mitarbeiter sollte in der Lage sein, Anomalien selber zu erkennen und ggf. korrekt zu behandeln.
    - Sicherheitsaspekte bei Realisierungsprojekten berücksichtigen: Jeder Verantwortliche der Linie sollte neue Projekte in Bezug auf die Sicherheit beurteilen und geeignete Massnahmen vorschlagen können.

49. Nennen Sie drei potenzielle Sicherheitsrisiken für Applikaitonen und zeigen sie auf, wie diese durch eine Benutzerschulung beeinflusst werden können. Antworten sie möglichst knapp.	￼

- Folgende Risiken können im Rahmen einer Benutzerschulung beeinflusst werden,
    - Fehlerquellen bei der Bedienung (z. B. durch Falscheingaben) können minimiert werden,
    - Die Benutzer sind in der Lage, Anomalien der Anwendung zu erkennen und zu melden,
    - Die Benutzer sind in der Lage, Sicherheitsoptionen der Anwendung korrekt einzustellen.

50. Führen Sie drei mögliche Themen bei der Schulung von IT-Sicherheitsmassnahmen an.

- Folgende Themen können bei der Schulung von IT-Sicherheitsmassnahmen im Vordergrund stehen:
    - Richtiger Einsatz der Passwörter
    - Korrekter Umgang mit E-Mails
    - Mustergültige Reaktion bei Notfällen

51. Jeder Mitarbeiter muss beim Eintritt den Erhalt der stellenbezogenen Sicherheitsweisungen schriftlich quittieren. Welche drei Vorteile entstehen für das Unternehmen dadurch?

- Eine schriftliche Quittierung hat für das Unternehmen folgende Vorteile:
    - Jeder Mitarbeiter kennt die Sicherheitsanforderungen, die für seine Arbeit relevant sind.
    - Jeder Mitarbeiter anerkennt seine persönliche Verantwortung bezüglich der IT-Sicherheit,
    - Der IT-Sicherheitsverantwortliche weiss, welcher Mitarbeiter über welche Pflichten informiert wurde.

52. Nennen Sie drei Sicherheitsmassnahmen, die beim Austritt eines Mitarbeitenden aus einem Unternehmen ergriffen werden können, und zeigen Sie den Nutzen dieser Massnahmen auf.

- Mögliche Sicherheitsmassnahmen beim Austritt eines Mitarbeiters:
    - Abgegebene Unterlagen zur IT-Sicherheit (Sicherheitskonzepte, -Weisungen, -richtlinien) zurückfordern. Dadurch kann das Risiko verringert werden, dass vertrauliche Dokumente oder Daten unkontrolliert in Umlauf gelangen und durch Dritte eingesehen werden.
    - Zutritts-, Zugangs-, Zugriffsrechte löschen. Dadurch wird verhindert, dass austretende Mitarbeitende weiterhin Zutritt zu Räumlichkeiten, Zugang zu Systemen bzw. Zugriff auf Daten und Informationen haben und dadurch das Unternehmen schädigen können.
    - Notfallpläne überprüfen und ggf. anpassen: Dadurch bleiben die Notfallpläne aktuell und die Nachfolge ist geregelt.

53. Welche Risiken können durch eine sorgfältige Rekrutierung und ein geordnetes Verfahren bei der Mitarbeitereinstellung reduziert werden? Listen Sie drei Beispiele auf.

- Folgende Risiken können durch eine sorgfältige Rekrutierung und ein geordnetes Einstellungsverfahren reduziert werden:
    - Hohe Fehlerrate bei Mitarbeitenden, die am falschen Ort eingesetzt werden
    - Häufiges Fehlverhalten durch Mitarbeitende, die sich nicht an der richtigen Stelle befinden.
    - Hohe Fluktuationsrate und somit hohe Kosten bei der Mitarbeiterrekrutierung.
    - Hohe Fluktuationsrate und somit stetiger Abfluss des Know-hows.

54. Nennen und charakterisieren Sie stichwortartig fünf Managementprozesse, die einen sicheren Systembetrieb gewährleisten können.

- Folgende Managementprozesse können einen sicheren IT-Betrieb gewährleisten:
    - Configuration Management: Hier wird sichergestellt, dass die IT-Infrastruktur vollständig und aktuell dokumentiert ist. Dadurch kann im Fall einer Störung richtig reagiert werden.
    - Change Management: Hier wird sichergestellt, dass Systemänderungen systematisch und nachvollziehbar durchgeführt werden. Dadurch können allfällige Fehler zurückverfolgt werden.
    - Release Management: Hier wird sichergestellt, dass neue oder geänderte Systemkomponenten systematisch getestet und kontrolliert ausgeliefert bzw. verbreitet werden.
    - Incident Management: Hier wird sichergestellt, dass Systemstörungen zentral erfasst und schnell und effizient behoben werden.
    - Problem Management: Hier wird sichergestellt, dass die Ursachen von (wiederkehrenden) Systemstörungen behoben werden.

55. Erläutern Sie in drei bis vier Sätzen, weshalb ein Entwicklungs- oder Beschaffungsprojekt ein Sicherheitsrisiko darstellen kann und welche organisatorische Massnahme sich empfiehlt.

- Wenn ein Entwicklungs- oder Beschaffungsprojekt falsche oder mangelhafte Ergebnisse liefert, kann der Systembetrieb gefährdet werden und es können wichtige Anwendungen oder Dienste ausfallen. Dies wirkt sich wiederum auf die entsprechenden Geschäftsprozesse aus und kann das ganze Unternehmen bedrohen. Ähnliche Probleme kann man sich einhandeln, wenn ein Entwicklungs- oder Beschaffungsprojekt zeitlich in Verzug gerät oder zu teuer wird. Aus diesen Gründen sind Projekte im Rahmen eines systematischen Projektmanagements abzuwickeln, das eine Anforderungsanalyse vorsieht, ein Projektcontrolling beinhaltet und den Projektfortschritt überwacht.

56. Zeigen Sie in ein bis zwei Sätzen den möglichen Nutzen eines Konzepts für die Verwaltung elektronischer Schlüssel auf.

- Ein Konzept für die Verwaltung elektronischer Schlüssel kann dazu beitragen, dass einheitliche elektronische Schlüssel verwendet werden und definierte Methoden bzw. Verfahren für die Schlüsselverwaltung zum Tragen kommen. Dadurch wird eine zentrale, nachvollziehbare Schlüsselverwaltung möglich.

57. Beschreiben Sie in zwei Sätzen die Merkmale organisatorischer Massnahmen.

- Organisatorische Massnahmen betreffen in der Regel die Strukturen und Prozesse eines Unternehmens. Betroffen sind Aufbau- und Ablauforganisation sowie die damit verbundenen Methoden und Verfahren.

58. Listen Sie die fünf Phasen des Life-Cycle-Managements auf.

- Die fünf Phasen des Life-Cycle-Managements lauten:
    - Spezifikation
    - Beschaffung/Realisierung
    - Deployment/Einführung
    - Betrieb
    - Entsorgung

59. Beschreiben Sie den Zweck und zwei Nutzenaspekte einer Benutzerkennung mit Passwort.

- Eine Benutzerkennung mit Passwort dient zur Identifikation oder Authentifikation der berechtigten Systembenutzer und soll verhindern, dass unbefugte Dritte Zugang zu einem bestimmten System bzw. zu einer bestimmten Applikation und/oder zu einem bestimmten IT-Dienst haben. Über die individuelle Benutzerkennung können den identifizierten bzw. authorisierten Benutzern entsprechende Rechte zugeordnet werden (z. B. Schreib- oder Leserechte). Weiter können die Aktivitäten in einem System protokolliert und den einzelnen Benutzern zugeordnet werden.

60. Mit welchen technischen Massnahmen würden Sie eine Arbeitsplatzstation bezüglich der Vertraulichkeit absichern? Nennen Sie drei Massnahmen im Hard- und Softwarebereich.

- Zum Schutz der Vertraulichkeit eignen sich u. a. folgende Massnahmen:
    - Gesichertes Login (User-ID und Passwort)
    - Zugangsbeschränkung (Benutzerrechte)
    - Bildschirmschoner (Screensaver)

61. Der Serverraum wird im Sommer zu heiss. Welche Sicherheitsmassnahme schlagen Sie vor und wer muss für die Planung und Umsetzung dieser Massnahme hinzugezogen werden?

- Als Massnahme bietet sich eine Klimaanlage an, die die Temperaturen im Serverraum reguliert und allzu hohe Temperaturen verhindert. Für die Planung und Umsetzung dieser Massnahme muss der Leiter der Infrastruktur hinzugezogen werden, weil bauliche Arbeiten damit verbunden sind.

62. Begründen Sie in zwei bis drei Sätzen, warum eine Gliederung der technischen Massnahmen in die Kategorien «Hardware und Software», «Kommunikation» und «Infrastruktur» Sinn macht.

- In vielen Unternehmen können die Kategorien «Hardware und Software», «Kommunikation» und «Infrastruktur» eigenen Fachabteilungen zugeordnet werden, sodass die zugehörigen Massnahmen in den gleichen Verantwortungsbereich fallen. Diese Fachabteilungen verfügen über entsprechende Spezialisten und das nötige Know-how, was die Koordination der Massnahmen vereinfacht und zu Kosten- und Zeiteinsparungen führt.

63. Gegen welche Gefahren sind Infrastrukturmassnahmen besonders geeignet? Nennen Sie zwei Bedrohungskategorien und begründen Sie Ihre Wahl aus Sicht der IT-Sicherheit in jeweils ein bis zwei Sätzen.

- Infrastrukturmassnahmen befassen sich in erster Linie mit dem Schutz von Gebäuden und Räumen und sind vor allem bei folgenden Bedrohungskategorien zu empfehlen:
    - Höhere Gewalt: Infrastrukturmassnahmen können Gebäude oder Räume, in denen sich wichtige Teile der IT-Infrastuktur (z. B. das Rechenzentrum) oder wichtige Komponenten des unternehmerischen ICT-Systems (z.B. die Server) befinden, wirkungsvoll vor Umwelteinflüssen und Naturgewalten schützen.
    - Vorsätzliche Handlungen: Infrastrukturmassnahmen können Gebäude oder Räume, in denen sich wichtige Teile der IT-Infrastuktur oder wichtige Komponenten des unternehmerischen ICT-Systems befinden, wirkungsvoll vor unberechtigtem Zutritt und Sabotage schützen.

64. Die Verordnung zum Datenschutzgesetz nennt mehrere Massnahmen zum Schutz personenbezogener Daten. Beschreiben Sie den Sinn und Zweck der Bekanntgabe-, der Benutzer- und der Transportkontrolle jeweils mit einem prägnanten Satz.

- Massnahmen zum Schutz personenbezogener Daten aus der VDSG:
    - Bekanntgabekontrolle: Damit wird sichergestellt, dass nachvollzogen werden kann, wem die Daten bekannt gegeben bzw. zugänglich gemacht wurden.
    - Benutzerkontrolle: Damit wird sichergestellt, dass die Identität eines Benutzers jederzeit ermittelt werden kann.
    - Transportkontrolle: Damit wird verhindert, dass Daten während des Transports von unbefugten Personen eingesehen werden können.

65. Wozu wird eine Sicherheitsstrategie für die Nutzung des World Wide Webs (WWW) benötigt und welche beiden Hauptelemente sollte sie enthalten?

- Eine solche Sicherheitsstrategie wird benötigt, um mögliche Gefahrenquellen bei der Nutzung des WWW kontrollieren zu können. Wichtige Bestandteile sind die möglichen Benutzerkreise und deren Risikopotenziale.

66. Was ist bei der Vergabe von E-Mail-Adressen und bei der Verwaltung von Verteilerlisten in Bezug auf die IT-Sicherheit zu beachten? Antworten Sie in zwei bis drei Sätzen.

- Eine E-Mail-Adresse muss einmalig und eindeutig sein, d. h., es muss klar sein, wer sie verwendet. Bei der Verwaltung von Verteilerlisten ist darauf zu achten, dass diese aktuell sind und restriktiv gehandhabt werden. Fehlgeleitete E-Mails wegen veralteter E-Mail-Adressen oder mangelnder Sorgfalt bei der Pflege von Verteilerlisten bergen ein hohes Risiko bezüglich der Vertraulichkeit.

67. Nennen Sie die drei Hauptfunktionalitäten eines Remote Access Systems und deren Zweck.

- Ein RAS umfasst folgende Hauptfunktionalitäten:
    - Authentifizierung: Dadurch wird sichergestellt, dass nur berechtigte Personen Zugang zum System erhalten.
    - Verschlüsselung: Dadurch wird die Vertraulichkeit während der Nutzung des Systems gewährleistet.
    - Protokollierung: Dadurch kann nachvollzogen werden, wer das System wann genutzt hat.

68. Nennen Sie drei Grundregeln für den korrekten Einsatz einer Firewall.

- Für den richtigen Einsatz einer Firewall gelten folgende Grundregeln:
    - Alle Kommunikationsvorgänge zwischen zwei Netzen müssen ohne Ausnahme über die Firewall geführt werden.
    - Die Firewall darf nur die Funktionalitäten der Firewall und keine anderen, zusätzlichen Dienste unterstützen.
    - Die Firewall darf ausschliesslich durch autorisiertes Personal über besonders geschützte Verbindungen administriert werden.

69. Erläutern Sie die wichtigen Punkte bei der Fehlerbehebung.

- Bei der Behebung von Fehlern ist es wichtig, deren Ursache anhand geeigneter Ursache-Wirkungs-Analysen zu eruieren, um die Fehler nachhaltig auszumerzen.

70. Erklären Sie kurz die Abkürzung SIEM.

- Die Abkürzung SIEM bedeutet Security Incident and Event Management, Dabei werden sicherheitsrelevante Vorfälle systematisch erfasst und ausgewertet und nötigenfalls Alarm ausgelöst und/oder Gegenmassnahmen eingeleitet.

71. Erklären Sie kurz den Begriff «aktives Netzwerkmonitoring».

- Beim aktiven Netzwerkmonitoring werden im Gegensatz zum passiven Monitoring aktiv Pakete in das Netzwerk eingeschleust, um das Verhalten des Netzwerks zu analysieren.

72. Was versteht man unter dem Begriff ROSI?

- ROSI steht für Return on Security Investment und ist eine Kennzahl, um die Wirtschaftlichkeit von Investitionen/Aufwände in Sicherheitsmassnahmen zu bewerten.

73. Zu welchem Zweck wird das Fischgräten-Diagramm verwendet?

- Das Ishikawa-Diagramm (auch Fischgräten-Diagramm) dient zur systematischen Fehlerursachenermittlung (auch Root Cause Analysis genannt)

74. Erklären Sie den Zweck eines Sicherheitsaudits in einem kurzen Satz.

- Beim Sicherheitsaudit wird der Istzustand eines definierten Sachverhalts oder Umfelds analysiert und beurteilt.

75. Nennen Sie die Schritte, die im Sicherheitsaudit dem Schritt «Durchführen» folgen.

- Die Schritte im Sicherheitsaudit nach «Durchführen» sind:
    - Dokumentation der Analyse
    - Konsolidierung der Statistiken
    - Präsentation an Geschäftsleitung und Empfehlungen abgeben

76. Was kann getan werden, wenn eine Sicherheitsmassnahme nicht umgesetzt wird, welche Möglichkeiten gibt es anstelle der Sicherheitsmassnahme?

- Der verantwortliche Prozesseigner (Process Owner) kann die Verantwortung für die NichtUmsetzung der Massnahme übernehmen, falls es betrieblich notwendig ist bzw. die Umsetzung der Sicherheitsmassnahme den Geschäftsbetrieb behindern würde. Dazu wird ein sogenanntes «Risk Acceptance»-Dokument erstellt und vom Prozesseigner unterschrieben.

77. Erläutern Sie den Unterschied zwischen Schwachstellenanalyse und Penetrationstest.

- Bei der Schwachstellenanalyse werden lediglich Schwachstellen identifiziert und dokumentiert, beim Penetrationstest wird versucht, die Schwachstellen auszunutzen, um zu verifizieren, dass die Schwachstellen auch effektiv ein Risiko darstellen.

78. Bei der Beauftragung einer Drittpartei mit einem Sicherheitstest (Ethical Hacking, Penetrationstest) ist ein Aspekt besonders wichtig. Welcher Aspekt ist gemeint?

- Der Haftungsausschluss für den Auftragnehmer und eine präzise Definition, welche Methoden und Eskalationsverfahren bei unvorhergesehenen Zwischenfällen angewendet werden sollen.

79. Erklären Sie den Unterschied zwischen Effektivität und Effizienz in kurzen Sätzen oder anhand von einem Beispiel.

- Effektiv ist eine Aussage zur Zielerreichung, dagegen bezeichnet Effizienz die Wirtschaftlichkeit.

80. Bei der Reifegradanalyse wird der sog. Maturitätsgrad eines Prozesses erhoben. Was sagt dieser Maturitätsgrad aus?

- Der Maturitätsgrad eines Prozesses dokumentiert den «Reifegrad» des Prozesses, d. h., zu welchem Grad dieser Prozess bereits umgesetzt ist. Zu diesem Zweck gibt es Bewertungsmodelle, allen voran das Capability Maturity Model, das verschiedene Maturitätsstufen festlegt.

81. Nennen Sie zwei Kennzahlen für IT-Sicherheit.

- Zwei Kennzahlen zur Informationssicherheit:
    - Erkennungsquote von bösartigen Attacken und Zwischenfällen auf Systemen und Applikationen
    - Anzahl offener Sicherheitsschwachstellen auf Systemen

82. Was wird mit der Analyse des Reifegrads eines Prozesses bezweckt?

- Die Reifegradanalyse sagt aus, welchen Erfüllungsgrad ein Prozess erreicht hat bezüglich der kontinuierlichen Verbesserung. Die Stufen reichen von «nicht umgesetzt» bis «kontinuierlich optimiert».

83. Welches Sicherheitskriterium ist bei verteilten Datenbanken besonders zu berücksichtigen, wo besteht das grösste Risiko?

- Die Konsistenz der verteilten Datensammlungen, d.h. Vollständigkeit und inhaltliche Richtigkeit der Daten in den verschiedenen Datenbanken.

84. Welche Anforderung ist bei der Aufzeichnung von Systemvorfällen (Logs) zu berücksichtigen?

- Die Aufzeichnungen müssen zur Auswertbarkeit und Zusammenführung verschiedener Logdateien zwingend zeitsynchron registriert werden. Dazu müssen die Systeme einen gemeinsamen Taktgeber (Systemuhr) mit einer zentralen Stelle synchronisieren.

85. Welcher Aspekt ist bei der Analyse von grossen Logdateien zu beachten?

- Durch die hohen Datenmengen, die bei Logdateien typischerweise anfallen, ist einerseits die Unterstützung durch Werkzeuge notwendig. Zudem sollen die anfallenden Ereignisse nach vorgegebenen Kriterien zusammengefasst werden (konsolidiert), um die Beurteilung zu vereinfachen.

86. Was ist unter dem Begriff «Security Cockpit» zu verstehen? Bitte kurz erläutern.

- Ein Security Cockpit ist ein zusammengefasster Bericht über den Sicherheitsstatus eines Unternehmens, der durch den Sicherheitsbeauftragten gepflegt wird und dem Management vorgelegt wird.

87. Welcher rechtliche Aspekt ist bei der Überwachung von Mitarbeitenden bzw. deren Tätigkeiten unbedingt zu berücksichtigen?

- Generell ist bei der Mitarbeiterüberwachung grosse Sorge zu deren Privatsphäre und Datenschutz zu geben. Die Überwachungsergebnisse sollen aufs Notwendigste beschränkt werden, ein Schritt-für-Schritt-Vorgehen ist zu wählen, um mögliche Verdachtsmomente zuerst zu konkretisieren, bevor weitere (persönlichkeitsrelevante) Details analysiert werden.

88. Beantworten Sie mit einer kurzen Begründung, ob Mitarbeitende ohne Vorwarnung überwacht werden dürfen.

- Grundsätzlich müssen die Mitarbeitenden informiert werden, bevor die Überwachung stattfindet. Wenn die Überwachung generell in einer Weisung geregelt ist, dürfen stichprobenartige Analysen vorgenommen werden, jedoch nur bei konkretem Verdacht. Präventive, personenbezogene Überwachung ist nicht gesetzeskonform.

89. Warum ist der Optimierungsschritt notwendig und wozu dient dieser Schritt?

- Durch ständige Optimierung der Massnahmen kann der Qualitätsregelkreis geschlossen werden. Oft wird in der Praxis zwar gemessen, aber die notwendige Anpassung bzw. Verbesserung der Massnahmen vernachlässigt. Letztlich kann der Aufwand durch Optimierung gemindert werden, was zu einem besseren Unternehmensergebnis führt.

90. Welche Art von Massnahmen wird bei der Optimierung umgesetzt? Nennen Sie dazu einen Begriff oder eine Erklärung.

- Massnahmenoptimierung geschieht auf die folgenden zwei Arten:
    - Korrigierend: Bestehende Massnahmen werden korrigiert und verbessert.
    - Präventiv: Meist neue (auch bestehende) Massnahmen werden eingeführt, um Risiken von Vornherein auszuschliessen.

91. Gibt es eine gesetzliche Grundlage zur Optimierung von Prozessen?

- Nein, es besteht keine gesetzliche Pflicht. Die Optimierung trägt jedoch zur Steigerung des Gewinns bei.

92. Wann werden Korrekturmassnahmen im Optimierungsschritt umgesetzt?

- Korrekturmassnahmen werden nach Analyse, Beurteilung und entsprechendem Umsetzungsvorschlag (bezüglich Optimierungsmöglichkeiten) durch das Management in Auftrag gegeben.

93. Warum ist eine stetige Optimierung des Sicherheitskonzepts notwendig?

- Die Risikolage sowie die Rahmenbedingungen sind ständigen Änderungen unterworfen, entsprechend muss das Sicherheitskonzept diesen Änderungen Rechnung tragen.

94. Erläutern Sie die Bedeutung der Risikokommunikation in einem kurzen Satz.

- Kunden, Mitarbeitende und nicht zuletzt die Öffentlichkeit haben Anspruch auf transparente Kommunikation über die aktuelle Situation des Unternehmens. Dazu gehört auch, über die bestehenden Risiken und Massnahmen zu informieren. Letztlich kann mit einer geeigneten Risikokommunikationspolitik ein Wettbewerbsvorteil gegenüber Konkurrenten erlangt werden.

95. Nennen Sie einen Bereich der IT, in dem Sicherheit oft mangelhaft umgesetzt wird.

- Die System- bzw. Anwendungsentwicklung berücksichtigt Sicherheitsanforderungen oft erst am Ende des Entwicklungsprozesses. Dies verteuert die Sicherheitsmassnahmen unnötig. Es ist wichtig, Sicherheitsanforderungen wie funktionale Anforderungen zu behandeln und am Anfang des Entwicklungsprozesses mit zu berücksichtigen.

96. Was ist vor der Umsetzung von Sicherheitsmassnahmen wichtig?

- Die Unterstützung des Managements, damit gewährleistet ist, dass genügend Ressourcen zur Verfügung gestellt werden.

97. Wie können Bedenken der Mitarbeitenden und Betroffenen bezüglich Risiken und Veränderung kontrolliert werden?

- Durch Buy-in der Betroffenen, indem diese frühzeitig über die Absichten informiert werden und Gelegenheit erhalten, ihre Bedenken zu äussern.

98. In der Softwareentwicklung ist Security by Design wichtig. Erläutern Sie kurz den Grund dafür.

- Die Umsetzung von Sicherheitsanforderungen bereits während der Entstehungsphase von Software bedeutet einen um ein Vielfaches reduzierten Aufwand; oft ist ein nachträglicher Einbau von Sicherheitsmassnahmen gar nicht mehr möglich, wenn das Designkonzept die Sicherheit nicht berücksichtigt hat.

99. In welchen Zeitabständen sollte eine IT-Sicherheitsstrategie angepasst werden?

- Sofern die Strategie nicht aufgrund externer Ereignisse angepasst werden muss, ist ein Zyklus von 3 bis 5 Jahren angebracht.

100. Welcher Aspekt ist, neben dem ausführlichen Testen und Proben, bei Notfallplänen wichtig?

- Die Ergebnisse der Notfalltests sind unbedingt in den Notfallplan einzupflegen. Der Notfallplan muss zu jedem Zeitpunkt aktuell gehalten werden, kleinste Nachlässigkeiten im Notfallplan können sich sonst verheerend auswirken.

101. Nennen Sie zwei typische Schwachstellen eines Notfallplans.

- Insbesondere die mangelnde Unterstützung durch das Management / die Geschäftsleitung, v.a. bezüglich Ressourcen, sowie fehlende oder unzureichende strategische Vorgaben sind zu erwähnen.

102. Nennen Sie zwei Gründe für die Änderung eines Sicherheitskonzepts.

- Wenn neue oder geänderte Gesetze im Sicherheitskonzept berücksichtigt werden müssen sowie Reorganisationen oder Fusionen von Geschäftsbereichen oder Organisationseinheiten.

103. Worin besteht das grösste Risiko bei der Überprüfung eines Notfallplans?

- Um einen Notfallplan gesamthaft testen zu können, muss eine Katastrophe simuliert werden, d.h., typischerweise werden sämtliche Systeme ohne Vorwarnung abgeschaltet. Vor allem bei unzureichender Erfahrung mit derartigen Tests kann es zu grossen Problemen beim Wiederanlauf kommen, was ein hohes betriebliches Risiko darstellt.

104. Was bezweckt der KVP? Begründen Sie in einem kurzen Satz.

- Der KVP ist ein wichtiger Bestandteil der Qualitätssicherung und bildet den Schlusspunkt des Plan-Do-Check-Act-Vorgehens. Mit der kontinuierlichen Verbesserung wird der Act-Prozess abgeschlossen und die Ergebnisse fliessen in einen (verbesserten) Plan-Schritt ein. Der Kreis schliesst sich, die kontinuierliche Verbesserung ist gegeben.

105. Welche Bereiche sind im Unternehmen vom KVP betroffen?

- Der KVP muss in der gesamten Unternehmensorganisation fest etabliert werden. Jeder Mitarbeiter ist verantwortlich, in seinem Bereich Verbesserungsmöglichkeiten zu identifizieren und die Verbesserungen umzusetzen. Entsprechend ist es wichtig, dass die Mitarbeitenden vom Management einen hohen Grad an Eigenverantwortung und -kompetenz erhalten, um die Umsetzung effektiv durchführen zu können.

106. Wie unterscheidet sich das TOM von der klassischen Qualitätssicherung?

- Beim TQM wird eine ganzheitliche Sicht angestrebt, die Umsetzung der Qualitätsanforderungen sowie die kontinuierliche Verbesserung werden der ganzen Organisation, anstatt einzelnen Mitarbeitenden, als Ziel gesetzt.

107. Nennen Sie zwei Methoden des KVP.

- Kaizen und TQM.

108. Nennen Sie das Hauptziel des KVP.

- Steigerung der Qualität und somit höhere Kundenzufriedenheit.


---
**Fett**

>Quote

![]()
