<h1 align="center">Sudhi S</h1>

<p align="center">
  <b>Technical Architect</b> · Healthcare · Insurance · Identity Management<br>
  <sub>Mobile → backend → data → AI. 14+ years shipping cross-platform systems.</sub>
</p>

<p align="center">
  <a href="https://sudhi.in"><img src="https://img.shields.io/badge/sudhi.in-0A0A0A?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="mailto:support@sudhi.in"><img src="https://img.shields.io/badge/support@sudhi.in-D14836?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/sudhis"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://x.com/su_dhi"><img src="https://img.shields.io/badge/@su__dhi-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"></a>
  <a href="https://bsky.app/profile/sudhis.bsky.social"><img src="https://img.shields.io/badge/Bluesky-0285FF?style=for-the-badge&logo=bluesky&logoColor=white" alt="Bluesky"></a>
</p>

---

I build systems end to end — Flutter and native mobile clients, the JVM/Go/Python services behind them, and the data pipelines that make them useful. Most of my work is in regulated domains, so HL7, encryption and identity are daily concerns rather than afterthoughts.

Technical Architect at **Stabilix Solutions** (Trivandrum, Kerala 🇮🇳) since 2013.

> **Currently building** — HL7 v2 developer tooling in Rust, native-backed Flutter storage plugins, and Go service libraries. Distribution via Homebrew and pub.dev.

---

## Featured work

### 🩺 [hl7probe](https://github.com/sudhi001/hl7probe) · Rust
Decodes and validates HL7 v2 messages from the terminal. Renames `PID-5` to *Patient Name*, turns `19850312` into *1985-03-12, age 41*, and tells you exactly what a receiving hospital system would reject — no integration engine, no server, one binary.

```sh
brew install sudhi001/tap/hl7probe
```
<sub>MIT · [Homebrew tap](https://github.com/sudhi001/homebrew-tap) · CI + changelog</sub>

### 📋 [FormStack](https://pub.dev/packages/formstack) · Dart
[![pub](https://img.shields.io/pub/v/formstack?style=flat-square&logo=dart)](https://pub.dev/packages/formstack) [![likes](https://img.shields.io/pub/likes/formstack?style=flat-square)](https://pub.dev/packages/formstack/score) [![downloads](https://img.shields.io/pub/dm/formstack?style=flat-square)](https://pub.dev/packages/formstack)

A cross-platform **ResearchKit and ODK alternative for Flutter** — dynamic forms and surveys with 35 input types, built from a declarative spec instead of hand-written screens.

### 💾 [native_datastore](https://pub.dev/packages/native_datastore) · Dart
[![pub](https://img.shields.io/pub/v/native_datastore?style=flat-square&logo=dart)](https://pub.dev/packages/native_datastore) [![likes](https://img.shields.io/pub/likes/native_datastore?style=flat-square)](https://pub.dev/packages/native_datastore/score) [![points](https://img.shields.io/pub/points/native_datastore?style=flat-square)](https://pub.dev/packages/native_datastore/score)

Persistent key-value storage for Flutter backed by **Android Jetpack DataStore** and **iOS UserDefaults** — the modern replacement for SharedPreferences. Ships with a [documentation site](https://sudhi001.github.io/native_datastore/), wiki guides and a security policy.

### 🔌 [TOML → Android strings.xml](https://plugins.jetbrains.com/plugin/24122-toml-to-android-strings-xml) · Kotlin
[![downloads](https://img.shields.io/jetbrains/plugin/d/24122?style=flat-square&logo=jetbrains)](https://plugins.jetbrains.com/plugin/24122-toml-to-android-strings-xml)

JetBrains Marketplace plugin that converts TOML localisation files into Android string resources. Companion Flutter widget: [toml_viewer](https://pub.dev/packages/toml_viewer).

### 🔐 [flutter_crypto_security](https://github.com/sudhi001/flutter_crypto_security) + [crypto_utils](https://github.com/sudhi001/crypto_utils) · Dart & Go
Matched client and server halves of one crypto contract — RSA/AES encryption with signature verification, [verified by a cross-platform test harness](https://github.com/sudhi001/encryption_cross_platform_test_flutter_go).

### 🌱 [SmartTerrarium](https://github.com/sudhi001/SmartTerrarium) + [SmartIOTConnect](https://github.com/sudhi001/SmartIOTConnect) · C++ & Dart
ESP32 terrarium automation driven by temperature and soil humidity, plus the Flutter app that provisions it over BLE. Firmware and companion app built as one system. See also [L_Spectra_Guardian](https://github.com/sudhi001/L_Spectra_Guardian), an ESP8266 air-quality and proximity monitor.

<details>
<summary><b>More open source</b></summary>

**Backend libraries (Go)**
- [kafka-event-consumer](https://github.com/sudhi001/kafka-event-consumer) — Kafka consumer library with a parallel worker pool and built-in health monitoring
- [badger_db_wrapper](https://github.com/sudhi001/badger_db_wrapper) — ergonomic wrapper over BadgerDB

**Healthcare**
- [HL7 → JSON (FastAPI)](https://github.com/sudhi001/HL7_TO_JSON_WITH_FAST_API) — HIPAA-conscious HL7 parsing service

**Developer tooling**
- [AndroidMacroBenchmarkViewer](https://github.com/sudhi001/AndroidMacroBenchmarkViewer) — visualise Android macrobenchmark output in the browser
- [logger_server](https://github.com/sudhi001/logger_server) — remote logging console for mobile developers
- [SFormUI](https://github.com/sudhi001/sfromui) — React form-wizard UI generated from JSON

**Earlier work**
- [couchbase-lite-java-plug](https://github.com/sudhi001/couchbase-lite-java-plug) — Couchbase Lite / Nitrite DB integration for JavaFX
- [UIGridView](https://github.com/sudhi001/UIGridView) — memory-efficient list adapters for Android
- [Bismillah](https://github.com/sudhi001/Bismillah) — Islamic prayer times app

</details>

---

## Tech

**Reaching for most days:** Dart/Flutter · Kotlin · Rust · Go · Java/Spring · Python · Swift · PostgreSQL · Kafka · AWS

<details>
<summary><b>Full stack, by category</b></summary>

| Category | |
|---|---|
| **Languages** | Java, Kotlin, Swift, Dart, Python, Go, Rust, JavaScript, C#, C, C++, Objective-C, PHP |
| **Mobile** | Flutter, Android (native), iOS (native), KMP/KMM, React Native, Ionic |
| **Backend & web** | Spring / Spring Cloud, Javalin, FastAPI, Flask, Node.js, .NET, Vapor, Next.js, React |
| **Desktop** | Flutter, SwiftUI, JavaFX, Electron |
| **Data & ML** | PyTorch, TensorFlow / TF Lite, Keras, CoreML, Spark, NiFi, Hive, Impala, Kudu |
| **Databases** | PostgreSQL, MySQL, MongoDB, SQLite, BadgerDB, Realm, Couchbase Lite, Neo4j |
| **Messaging** | Kafka, RabbitMQ, ActiveMQ, ZeroMQ, MQTT |
| **Protocols & formats** | REST, gRPC, GraphQL, WebSocket, WebRTC, SOAP, HL7 v2, Protobuf, Avro, Parquet |
| **Cloud & serverless** | AWS (EC2, S3, SNS, SQS, CloudFront, Amplify), Firebase, Supabase |
| **CI/CD & tooling** | GitHub Actions, Jenkins, Fastlane, Homebrew, Playwright |
| **Embedded** | ESP32, ESP8266, Raspberry Pi, Arduino, MicroPython, Embedded Swift |
| **Architecture** | Microservices, MVVM, MVI, VIPER, MVP, MVC |

</details>

---

## Experience

**Technical Architect** — Stabilix Solutions · 2013–present
Architect systems across healthcare, insurance and identity: big-data analytics pipelines, VOIP/chat frameworks, recommendation engines, and cross-platform Flutter apps spanning mobile, web and desktop. Mentor engineers and translate business requirements into technical design.

**Software Engineer** — Zayan Infotech · 2012–2013
Full-stack development across hospitality, education and utility products; led system integration testing.

<sub>Full history on <a href="https://www.linkedin.com/in/sudhis">LinkedIn</a>.</sub>

---

<div align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=sudhi001&show_icons=true&hide_border=true&theme=transparent&hide=contribs" alt="GitHub stats">
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sudhi001&layout=compact&hide_border=true&theme=transparent&langs_count=8&exclude_repo=vscode,flutter,awesome-go" alt="Top languages">
</div>

<p align="center">
  <a href="https://sudhi.in">sudhi.in</a> ·
  <a href="mailto:support@sudhi.in">support@sudhi.in</a> ·
  <a href="https://www.linkedin.com/in/sudhis">LinkedIn</a>
</p>
