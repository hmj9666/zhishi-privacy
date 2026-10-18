---
layout: default
title: ZhiShi Privacy Policy
lang: en
permalink: /en/
---

# ZhiShi Privacy Policy

- Effective date: 2026-10-18
- Operator: Huang Jianxin (黄建鑫)
- Contact email: [hjx966@163.com](mailto:hjx966@163.com)
- This page: <https://hmj9666.github.io/zhishi-privacy/en/>
- 中文版：<https://hmj9666.github.io/zhishi-privacy/>

This policy explains how ZhiShi (织识), an app for iPhone, iPad, and Mac, handles your information.

## 1. What ZhiShi is

ZhiShi is a personal knowledge library on your device. You can keep text, recordings, photos, and videos, organize knowledge cards, and, only after you agree, send selected text to an AI service you configure yourself.

ZhiShi is not a medical device. It is not for diagnosis or treatment, and it does not measure vital signs with device sensors. Clinical text in a card is your note. AI output is an editable suggestion and does not replace knowledge you have confirmed until you accept it. Consult a qualified clinician before making a medical decision.

## 2. Who is responsible

ZhiShi is operated by an individual developer, Huang Jianxin. For privacy questions, email [hjx966@163.com](mailto:hjx966@163.com).

ZhiShi has no developer-operated account system or server. Your library stays on your device by default, and the developer cannot sign in to or read it.

## 3. Data that stays on your device

The following is stored in the local library or in system facilities on your device and is not uploaded to the developer:

- Knowledge cards, the nine text modules, connections, folders, tasks, and confirmation records.
- Photos you take, videos you record, and audio you save.
- This app's own settings, such as language, appearance, and speech.
- API keys you save for AI services, kept in the device Keychain as "this device only, after first unlock."
- A local audit of AI requests (model, destination, whether sources or connections were included, whether redaction occurred, status, and an error summary), capped at 100 entries. It contains no API key and stays on the device.

Deleting the app removes the local library in the app container; Keychain retention follows Apple's rules. You keep any archive you export. You can set a passphrase when exporting; the archive is then encrypted on the device with AES-256-GCM, and the passphrase is not written into the archive.

## 4. iCloud and sync

ZhiShi 1.0 does not turn on iCloud sync or iCloud backup, and your library is not uploaded to iCloud. The Mac app uses its own local library, runs in the App Sandbox, has no network access, and only reads and writes files you choose in a system panel.

The share extension and widget exchange data with the app on the device through an App Group and do not contact the network themselves.

## 5. External AI services

External AI services are off by default. Selected text leaves your device only after you obtain your own API key, enable a service in Settings, and confirm each send.

| Service | Default host | Notes |
| --- | --- | --- |
| Apple Foundation Models | None (on device) | Content stays on this device. |
| OpenAI | api.openai.com | Content is sent to OpenAI. |
| Anthropic | api.anthropic.com | Content is sent to Anthropic. |
| DeepSeek | api.deepseek.com | Content is sent to DeepSeek. |
| Kimi | api.moonshot.cn | Content is sent to Kimi (Moonshot AI). |
| Custom endpoint | The URL you enter | Content is sent to the address you provide. |

Four kinds of actions can send text to an external service: invoking knowledge, filling or optimizing the nine modules, translating a module between Chinese and English, and translating a media caption or transcript. They share one confirmation sheet:

- **Redaction on the device before sending.** Before the sheet opens, ZhiShi masks the content to be sent, including email addresses, mainland China mobile numbers, 18-digit national ID numbers, medical-record and visit numbers, insurance-card numbers, labeled dates of birth, patient names, family-member names, bed numbers, visit dates, and hospital departments. Matches are replaced with placeholders such as "[Redacted · label]" and are not restored before sending. This is not complete de-identification: diagnoses, symptoms, medications, and other text that does not match these patterns remain on the sheet, and you decide whether to send them.
- **Confirmation for every request.** The confirmation switch starts off, and nothing is sent without it. Closing the sheet sends nothing, and the next request needs a new confirmation. If the content changes after you confirm, that request is rejected.
- **Only what you saw is sent.** The text sent is the redacted text shown on the confirmation sheet.

Apple Foundation Models run on the device and the text does not leave it. If that model is unavailable, the request fails and is never rerouted to a cloud service.

AI replies are suggestions for you to review and do not overwrite confirmed content until you accept them. How an external service stores data, whether it uses data for training, and where it processes data are governed by that service's own privacy policy. ZhiShi does not sign contracts with these providers on your behalf. For text already sent to a third party, request access or deletion from that provider.

**Cross-border note (not legal advice):** If you are in mainland China and send personal information to a service outside mainland China, review the Personal Information Protection Law of the People's Republic of China, including its rules on sensitive personal information and cross-border provision. Medical and health information is sensitive personal information under that law.

## 6. Dictation, camera, and microphone

- **Dictation is recognized on the device only.** ZhiShi uses Apple speech recognition only when you start dictation and requires on-device recognition. Audio is not sent to Apple or any other recognition service. If the device or language does not support on-device recognition, ZhiShi tells you and stops; it never falls back to cloud recognition.
- The **camera** attaches photos to knowledge cards and records teleprompter practice videos. The **microphone** is used for dictation, voice memos, and the sound in practice videos. These photos, videos, and recordings stay in your library and are not uploaded to the developer.

## 7. Tracking, ads, and analytics

ZhiShi does not track you, contains no advertising SDK, does not request App Tracking Transparency permission, and has no developer-operated analytics upload.

Under Apple's definition of "collection," ZhiShi reports the following two data types. Both are used for app functionality, are not linked to your identity, and are not used for tracking:

- **Health:** clinical content you provide in knowledge cards, sent to the external AI service you choose only after you confirm.
- **Other User Content:** knowledge text you confirm for an external AI service.

Photos, videos, and dictation audio stay on the device and are not collected. If a future feature uploads audio, we will report it and update this policy.

## 8. Your choices

- Leave external AI services disabled, and external models are never called.
- Every cloud send requires your agreement on that request's confirmation sheet, and you can cancel at any time.
- When invoking knowledge, you can leave out sources and turn off connections.
- You can delete cards, export an archive, or delete the app to remove the local library.
- You can turn off camera, microphone, or speech recognition access in system Settings at any time. ZhiShi cannot recall a request already received by another party's server.

## 9. Children

ZhiShi has no child accounts and does not knowingly collect children's personal information. If you believe a child has sent personal information to an external service through ZhiShi, please contact us.

## 10. Changes to this policy

When this policy is updated, we will publish the new version on this page and change the effective date. Material changes will also be noted in the app's release notes.

## 11. Contact

Privacy questions: Huang Jianxin, [hjx966@163.com](mailto:hjx966@163.com).
