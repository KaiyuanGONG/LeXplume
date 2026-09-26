<p align="center">
  <img src="assets/logo-512.png" alt="LeXplume Semantic Fold logo" width="96">
</p>

# LeXplume

## Turn the words you come across into words you remember.

Capture words from papers, reports, slides, and the French you meet in daily life. Get explanations for your field, suggestions drawn from your own library, and reviews scheduled by FSRS.

[简体中文](README.md) · [Français](README.fr.md)

[Live preview](https://lexplume.com) · [Product logic](PRODUCT.md) · [FAQ](FAQ.md) · [Support](mailto:support@lexplume.com) · [Privacy](https://lexplume.com/privacy)

> `lexplume.com` currently shows LeXplume 1.0.0. A free, invite-only Early Access for adults (18+) learning on their own is being prepared; public registration, payment, and a Google Play release are not available yet.

![LeXplume selecting aligned and embeddings from technical material while preserving each source sentence](assets/readme/01-capture-real-material.webp)

_Captured from the live LeXplume 1.0.0 interface with fictitious demo data._

## Capture from your material, not somebody else's list

LeXplume starts with what you are already reading. Enter a word, paste a sentence or paragraph and select several targets, or extract text from an image with OCR. Each saved word keeps its sentence, source, tags, and capture time, so when you review it later you can still see where it came from.

It works well for papers, technical reports, lecture slides, and the French you run into in daily life.

## Explanations for your field

The same word can mean very different things in different fields. Enter your field in Settings (for example, “bioinformatics”) and LeXplume adds an explanation for that field next to the dictionary definition.

Take `alignment`:

- In general usage, it can mean arrangement or agreement.
- In bioinformatics, it usually means **sequence alignment** across DNA, RNA, or proteins.
- In machine learning, `model alignment` concerns keeping model behaviour consistent with human intentions, norms, or goals.

The short meaning, dictionary definition, and domain explanation are shown separately. A domain explanation is saved once generated, so opening the word again does not need another request.

![LeXplume comparing the general definition of alignment with its bioinformatics and machine-learning meanings](assets/readme/02-domain-explanation.webp)

## Suggestions that grow with your library

LeXplume looks at your study language, your field, the difficulty you choose, your recent captures, your tags, and the words FSRS marks as weak, then suggests a mix of:

- adjacent concepts that extend topics you already study;
- useful collocations, derivatives, and word families;
- reinforcement for areas where recall is still weak.

Words already in your library are never suggested. Suggestions stay temporary until you tap Add. With a new or empty library, suggestions are based on your field and difficulty only.

## English and French, each with its own learning rhythm

English and French share one local data model and backup format, while keeping separate library views, recommendations, and review queues. French study uses a cool-blue ambience and visible `FR` markers; English keeps the warm-amber ambience and remains unmarked.

One review session covers one language, avoiding mixed English/French cards. Disabling French study hides French entries without deleting them.

![Side-by-side comparison of LeXplume's warm-amber English library and blue French library with FR markers](assets/readme/03-english-french.webp)

_Side-by-side composition of two real interface states, both using fictitious data._

## Review with FSRS

LeXplume uses FSRS to schedule each word's next review from your rating, with four practice modes: flashcard, spelling, dictation, and sentence fill-in. The dashboard shows due words, retention, streaks, activity, and how many words are in each state.

| Capability | How LeXplume handles it |
| --- | --- |
| Capture | Words, sentences, paragraphs, and image/OCR input; select several targets at once |
| Understand | Pronunciation, dictionary definition, concise Chinese meaning, cached domain explanation, and per-word follow-up |
| Recommend | Uncaptured words selected from language, domain, difficulty, recent vocabulary, and weak areas |
| Review | FSRS scheduling with flashcard, spelling, dictation, and sentence fill-in modes |
| English / French | Separate library, recommendation, and review flows; blue French ambience with `FR` markers |
| Data | Browser-local storage, offline-capable core, and JSON export/import |
| Cloud | Optional account sync and Cloud AI (daily limit); the app always works from the copy on your device |

## Local data and API keys

- **Local by default.** Active vocabulary and review state live in the browser; core capture and review work offline.
- **Portable backup.** Data can be exported to and restored from JSON.
- **Browser-direct BYOK.** Choose an AI provider and model and supply your own key. The key stays on the device and is excluded from JSON export and sync.
- **Sync is optional.** It keeps a copy in the cloud for your other devices; the app still works from the copy on this device.
- **Cloud AI is optional too.** It is available only to invited accounts, with a daily limit, and you never need it to use LeXplume.

Read the current [privacy policy](https://lexplume.com/privacy) before enabling optional AI features. Only the content needed for the current request is sent to the AI provider.

## Current availability

- The official app is the Web/PWA at [lexplume.com](https://lexplume.com), currently version 1.0.0.
- Accounts and Cloud AI are still in pre-launch testing and open to invited accounts only.
- Known gap: AI enrichment for French words fills in part of speech, a French definition, and a short Chinese meaning, but not yet the IPA transcription.
- Public registration, payment, and public Google Play distribution are not available. See [ROADMAP.md](ROADMAP.md) and [RELEASE_NOTES.md](RELEASE_NOTES.md).
- LeXplume is not currently promoted or supported in mainland China.

## Design point of view

The interface style is called **Paper**: warm off-white backgrounds, serif headings, little decoration, and plenty of space, so attention stays on the word and its sentence. The **Semantic Fold** logo is one continuous shape with an open space inside, standing for language being captured, understood, and kept. It still reads in a single colour and at small sizes.

Read the full [product and design rationale](PRODUCT.md).

## Feedback and repository scope

Use the product-feedback issue form for suggestions that contain no personal information. Account-specific support belongs at [support@lexplume.com](mailto:support@lexplume.com), and security concerns must follow [SECURITY.md](SECURITY.md).

This is a public product-information repository containing release notes, support guidance, public product direction, and approved brand/media assets. It does not contain application source code; the source remains private. Publication does not grant a licence to the LeXplume application, name, visual identity, or private code.
