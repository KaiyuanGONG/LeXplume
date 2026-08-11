<p align="center">
  <img src="assets/logo-512.png" alt="LeXplume Semantic Fold logo" width="96">
</p>

# LeXplume

**Turn the words you meet in real reading into vocabulary you can actually recall.**

[简体中文](README.zh-CN.md) · [Français](README.fr.md)

![LeXplume — words in context, review on rhythm](assets/github-hero-1600x600.png)

[Website](https://lexplume.com) · [Product logic](PRODUCT.md) · [Support](mailto:support@lexplume.com) · [Privacy](https://lexplume.com/privacy)

LeXplume is a Chinese-first English and French vocabulary app for independent adults. It connects the words you encounter in real material with their original sentence, a concise explanation, and an FSRS review schedule—without making a cloud account or AI subscription the centre of the experience.

## Why LeXplume

- **Generic word lists start outside your life.** LeXplume begins with material you already chose to read.
- **Contextless lookup is easy to forget.** Every captured word can keep the sentence that made it meaningful.
- **Manual card creation interrupts reading.** Capture, explanation and review stay in one focused flow.
- **Cloud-only learning reduces control.** Core vocabulary and review state remain local-first, with offline-capable use and JSON backup.

## The learning loop

**Encounter → Capture → Understand → Review → Retain**

1. **Encounter** a useful English or French word in something you are reading.
2. **Capture** the word or phrase together with its sentence.
3. **Understand** it with dictionary context and optional AI assistance.
4. **Review** it when FSRS estimates that memory needs reinforcement.
5. **Retain and reuse** it through recall, spelling, dictation and sentence exercises.

## What it includes

- Text and image-text capture that preserves sentence context.
- A local-first vocabulary library with JSON export and restore.
- FSRS review using flashcards, spelling, dictation and sentence completion.
- English study by default and opt-in French study.
- Independent interface, explanation and studied-content languages.
- Optional browser-direct AI with a locally stored key; eligible invited accounts may use a bounded managed service.
- Optional account sync as a cloud mirror, not the runtime source of truth.

## Product preview

These are unedited captures from the real LeXplume interface using fictitious learning content.

| Capture in context | Review with FSRS | Keep local control |
| --- | --- | --- |
| <img src="assets/screenshot-capture.jpeg" alt="Select a word in its original sentence" width="280"> | <img src="assets/screenshot-review.jpeg" alt="Review a word with four recall ratings" width="280"> | <img src="assets/screenshot-local-first.jpeg" alt="Local mode and JSON backup controls" width="280"> |

## Design point of view

LeXplume uses a quiet **Paper** visual language: warm neutral surfaces, editorial typography, restrained hierarchy and enough space to keep attention on the word and its sentence. The **Semantic Fold** mark uses one continuous form and one negative-space focus to represent language being captured, understood and retained. It remains recognizable in one colour and at small sizes.

Read the full [product and design rationale](PRODUCT.md).

## Current availability

LeXplume 1.0 is being prepared as a free, invite-only Beta for independent adults aged 18+. Public registration, payment and a public Google Play release are not available at this time. Mainland China is not an actively supported launch market.

The Web/PWA at [lexplume.com](https://lexplume.com) is the canonical product. An Android Trusted Web Activity is in pre-release testing and will be distributed only after association, privacy and device checks pass.

## Data posture

LeXplume is local-first: the active vocabulary and review state live in browser storage. Optional account sync is a cloud mirror rather than the runtime source of truth. Browser-direct AI keys stay on the device and are excluded from JSON export and sync.

Optional AI features send only the content needed for the requested operation to the provider you select or to LeXplume's managed proxy. Read the current [privacy policy](https://lexplume.com/privacy) before enabling them.

## Feedback and repository scope

Use the product-feedback issue form for non-private suggestions. Account-specific support belongs at [support@lexplume.com](mailto:support@lexplume.com), and security concerns must follow [SECURITY.md](SECURITY.md).

This is a public product-information repository. It contains release notes, support guidance, public product direction and approved brand/media assets. It does not contain the application source code; the source remains private. Publication does not grant a license to the LeXplume application, name, visual identity or private code.
