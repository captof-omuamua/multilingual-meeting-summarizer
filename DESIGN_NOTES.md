# Recovered design notes

The September 2024 software-engineering document defines objectives and a proposed solution for a Tamil/Telugu meeting summarizer. It is a requirements/design artifact, not evidence of an implemented service.

## Planned flow

1. Accept meeting audio and supporting text/chat notes.
2. Transcribe speech using a language-appropriate ASR model.
3. Select important sentences or generate an abstractive summary.
4. Translate Tamil/Telugu text according to the participant's chosen language.
5. Present transcript, summary, and translation views; optionally export records.

## Candidate technologies in the proposal

The document lists Whisper or cloud ASR; BART, Pegasus, or mT5-family summarization options; IndicTrans/mT5 translation; React or Angular interfaces; Python/Node.js services; and cloud storage. These are alternatives considered in a proposal, not verified deployed dependencies.

## Planned requirements

Brief/detailed summaries, language switching, cross-platform access, domain adaptation, meeting-platform integration, secure storage, authentication, and scalability appear as proposed requirements. No latency, WER, ROUGE, translation score, user study, deployment record, or matching source implementation was recovered in this folder.

## Relation to other coursework

The meeting application scope differs from the Tamil text-summarization experiments, the Tamil-to-Telugu speech-translation prototype, and the later Malayalam headline/Phase 2 research archive. Shared NLP components do not establish a shared implementation; those projects remain separate.

Only diagrams and anonymized design summaries are published. The report cover, revision authors, and activity log are excluded.
