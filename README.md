# Offline Voice Engaging System

An offline, on-device AI assistant that helps people understand notices,
forms and scheme paperwork, and write applications, in their own language
with no internet.

**Live demo:** https://hansika4301.github.io/voice-engaging-system/

> This is an interactive prototype with sample data. Voice, scanning and
> AI replies are simulated. A real on-device version is planned.

## The problem
Many people in India, such as farmers, small shopkeepers and rural clinic
workers, struggle to understand forms, government notices and scheme
paperwork. Internet is often weak, most AI tools work best in English and
need the cloud, and uploading personal documents online is a privacy risk.

## Our solution
A phone-first assistant that runs a small open-source AI model on the
device, using the phone's NPU, so it works fully offline.

## Pages in this prototype
- **Home:** status, shortcuts and recent items
- **Talk:** ask by voice and get an answer in your language
- **Scan:** photograph a notice and get a simple explanation, the documents
  needed and the last date
- **Write:** draft a letter or fill a scheme form, then save as Word or PDF
  or send to a laptop with Office Kit
- **Records:** documents saved on the phone
- **Settings:** offline mode, on-device model details and privacy

## Planned on-device version
- On-device speech recognition and speech output in local languages
- Small open-source language model running on the phone's NPU
- Camera document reading
- Local storage of records, with optional sync when online
- Word and PDF export, and transfer to a laptop with Office Kit

## Planned tech stack
- Android app (Kotlin or Flutter)
- Small open-source language model running on-device
- Offline speech recognition and text-to-speech
- On-device document reading (OCR)
- Local database for saved records
- Word and PDF export, with transfer to a laptop
