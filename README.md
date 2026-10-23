<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" width="100%" alt="Chaima Gabsi, software engineer in Stuttgart, Germany. Real-time AI and full-stack applications for digital health.">
</picture>

<br>

<p align="center">
  <a href="https://www.linkedin.com/in/shayma-gabsy-1a6024342/"><img src="https://img.shields.io/badge/LinkedIn-Chaima%20Gabsi-7B66B4?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:shaymagabsy9@gmail.com"><img src="https://img.shields.io/badge/Email-shaymagabsy9%40gmail.com-A9567F?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Based%20in-Stuttgart%2C%20Germany-5F4B93?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Based in Stuttgart, Germany">
</p>

### About me

I'm a software engineer in Stuttgart. I build applications that run in real time and handle sensitive data: voice conversations, emotion signals, clinical records. I work across the whole stack, from a model running on the user's device to the API, the web client and the mobile app.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/highlights-dark.svg">
  <img src="assets/highlights-light.svg" width="100%" alt="3 emotion channels: face, words, voice tone. 4 apps I work on: web, iOS, portal, website. 6 languages on the marketing site. More than 400 commits on EmpAItica since May 2026.">
</picture>

### Now: EmpAItica at ACTIMI

Engineering thesis at **ACTIMI GmbH** in Stuttgart. **EmpAItica** is an AI application that helps detect depression early and follow patients between consultations. The patient talks with a 3D avatar and answers the PHQ-8 questionnaire by voice. The clinician sees the scores and their trend in a dedicated portal.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/flow-dark.svg">
  <img src="assets/flow-light.svg" width="100%" alt="How a session flows: voice conversation, face read on the device, words and voice tone, emotion fusion, HL7 FHIR R4 record, clinician portal.">
</picture>

- **Emotion from three channels.** Face analysis on the device with MediaPipe and ONNX Runtime, a bilingual English and German word lexicon, and a voice tone model (emotion2vec+) served by a FastAPI service.
- **A stable signal.** Smoothing and fusion of the three readings, so the emotion shown to the patient stays steady instead of flickering.
- **Real-time conversation.** Voice-to-voice dialogue over WebSocket, with a 3D avatar built in three.js.
- **Clinical data.** HL7 FHIR R4 resources and a crisis path that no setting can turn off.
- **The apps around it.** React web client, iOS app with Expo and React Native on TestFlight, clinician portal with online video consultations, administration, and a marketing site in six languages.
- **Privacy by design.** Face analysis stays on the device. No camera image is sent to the server.

The code belongs to ACTIMI and stays private. Live product: [empaitica.com](https://www.empaitica.com)

<img src="assets/divider.svg" width="100%" alt="">

### Tech stack

| Area | Technologies |
|---|---|
| **Languages** | ![TypeScript](https://img.shields.io/badge/TypeScript-5F4B93?style=flat-square&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-5F4B93?style=flat-square&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-5F4B93?style=flat-square&logo=openjdk&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-5F4B93?style=flat-square&logo=postgresql&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-7B66B4?style=flat-square&logo=react&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-7B66B4?style=flat-square&logo=nextdotjs&logoColor=white) ![React Native](https://img.shields.io/badge/React%20Native-7B66B4?style=flat-square&logo=react&logoColor=white) ![Expo](https://img.shields.io/badge/Expo-7B66B4?style=flat-square&logo=expo&logoColor=white) ![three.js](https://img.shields.io/badge/three.js-7B66B4?style=flat-square&logo=threedotjs&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-7B66B4?style=flat-square&logo=tailwindcss&logoColor=white) |
| **Backend** | ![NestJS](https://img.shields.io/badge/NestJS-A9567F?style=flat-square&logo=nestjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-A9567F?style=flat-square&logo=fastapi&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-A9567F?style=flat-square&logo=springboot&logoColor=white) ![WebSocket](https://img.shields.io/badge/WebSocket-A9567F?style=flat-square&logo=socketdotio&logoColor=white) |
| **AI** | ![ONNX Runtime](https://img.shields.io/badge/ONNX%20Runtime-5F4B93?style=flat-square&logo=onnx&logoColor=white) ![MediaPipe](https://img.shields.io/badge/MediaPipe-5F4B93?style=flat-square&logo=google&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-5F4B93?style=flat-square&logo=pytorch&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI%20Realtime-5F4B93?style=flat-square&logo=openai&logoColor=white) |
| **Data and tools** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-7B66B4?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-7B66B4?style=flat-square&logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-7B66B4?style=flat-square&logo=docker&logoColor=white) ![Railway](https://img.shields.io/badge/Railway-7B66B4?style=flat-square&logo=railway&logoColor=white) ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-7B66B4?style=flat-square&logo=opentelemetry&logoColor=white) ![Git](https://img.shields.io/badge/Git-7B66B4?style=flat-square&logo=git&logoColor=white) |
| **Health and compliance** | ![HL7 FHIR R4](https://img.shields.io/badge/HL7%20FHIR%20R4-A9567F?style=flat-square) ![GDPR by design](https://img.shields.io/badge/GDPR%20by%20design-A9567F?style=flat-square) |

### Experience and education

| When | What and where |
|---|---|
| **2026** | Software engineer, engineering thesis · **ACTIMI GmbH**, Stuttgart |
| **2025** | Data and BI intern · **Hewlett-Packard**, Tunisia |
| **2025** | Exchange semester · **Philipps-Universität Marburg**, Germany |
| **2023, 2024** | Software development intern · **ESPRIT**, Tunisia |
| **2022 to 2026** | Master's degree in computer engineering · **ESPRIT**, Tunis |

### Languages

Arabic (native) · French (B2) · English (B2) · German (A2)

<img src="assets/divider.svg" width="100%" alt="">

<p align="center"><i>Thanks for visiting. Feel free to reach out on LinkedIn.</i></p>
