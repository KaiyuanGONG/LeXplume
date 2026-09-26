# Product and design logic

LeXplume helps adults who learn on their own turn words they meet in English or French material into vocabulary they can review and remember. The product is Chinese-first, local-first and works offline; AI and cloud features are optional.

## The problem

### Generic word lists begin without intent

Generic word lists are efficient to distribute but disconnected from the learner's current interests, field and reading. LeXplume starts with a word the learner has already noticed in material they chose.

### Contextless lookup loses the reason a word mattered

Contextless lookup answers “what can this word mean?” but often discards “what did it mean here?” LeXplume keeps the source sentence beside the word so explanation and later recall share the same anchor.

### Manual card creation breaks the reading flow

Manual card creation asks the learner to copy a word, sentence, definition and metadata across tools. That friction leads people to collect fewer words or make thinner cards. LeXplume handles capture, explanation and scheduling in one place.

### Cloud-only learning weakens control

With cloud-only products, you may need a login, a connection or an active account with a provider just to reach your own vocabulary. LeXplume keeps the active library and review state in local browser storage, supports JSON backup, and treats sync as an optional mirror.

## The learning loop

**Encounter → Capture → Understand → Review → Retain and reuse**

### 1. Encounter

The learner meets a useful word or phrase while reading material with a real purpose: an article, paper, story, document or image.

### 2. Capture

The learner selects the word and preserves its sentence. The unit of learning is therefore not an isolated spelling but a word-in-context.

### 3. Understand

Dictionary results work without AI. Optional AI can add an explanation based on the sentence, your field and your chosen explanation language. You can use your own key, which stays on your device, or, with an invited account, Cloud AI with a daily limit.

### 4. Review

FSRS estimates when another retrieval attempt is useful. Flashcard, spelling, dictation and sentence exercises vary the form of recall without changing the scheduling source of truth.

### 5. Retain and reuse

The goal is to recognize the word the next time you meet it in real material, not to grow a streak or a long list.

## Product boundaries

- **Local-first:** Indexed browser storage is the active runtime copy.
- **Offline-capable:** capture, library, backup and review remain useful after the app has loaded; network features still need connectivity.
- **Optional cloud mirror:** supported records can sync for eligible accounts, but sync is not required.
- **Optional AI:** basic vocabulary and review need neither your own AI key nor Cloud AI.
- **Independent language axes:** interface language, explanation language and studied-content language are separate settings.
- **User-controlled backup:** JSON export and restore let you move or recover your data yourself.

## Design rationale

### Paper

The interface uses the Paper direction only: warm neutral surfaces, restrained borders, editorial display type and generous spacing. Vocabulary work already carries dense linguistic information, so the visual system reduces competing decoration and keeps hierarchy predictable.

### Semantic Fold

The LeXplume mark is named **Semantic Fold**. One continuous asymmetric body surrounds one off-centre negative-space focus. The outer form represents language being gathered and transformed; the aperture represents the precise meaning held inside a larger context.

The mark follows four constraints:

1. one continuous subject;
2. one negative-space focal point;
3. at least 45% empty canvas; and
4. recognition in a single flat colour.

Paper ink is the primary treatment. A light reversed mark exists only as an adaptation for a genuinely dark field, not as a competing logo.

### Why the interface stays quiet

LeXplume is a reading and review tool, not a vocabulary game. Motion, colour and status indicators are there to help you act or understand, not to create pressure.

## What LeXplume does not claim

LeXplume does not guarantee retention, fluency, examination results or medical/cognitive outcomes. It is not currently a public signup service, a paid service, a public Google Play release or a child-directed product. The application source remains private. Availability statements on [lexplume.com](https://lexplume.com) take precedence over this overview.
