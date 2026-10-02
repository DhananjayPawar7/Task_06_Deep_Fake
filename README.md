# Task 06 — Constructing and Evaluating Synthetic Media

> **SYNTHETIC MEDIA DISCLOSURE**
>
> The audio artifacts contained in this repository were synthetically
> generated using AI for an academic research experiment. They do not
> represent a recording of a real person and do not clone the voice of
> an identifiable individual.

## Project Overview

This project examines the construction and evaluation of AI-generated
synthetic audio.

A single analytical narrative was converted into synthetic speech using
ElevenLabs Text to Speech.

Two attempts were generated using the same script, model, and synthetic
voice while varying Stability and Similarity settings.

The purpose was to evaluate how these settings influenced synthetic
speech and to document both the strengths and limitations of the
resulting artifacts.

## Task 5 / Source Material Note

I did not complete Task 5 before beginning this task. I therefore
prepared a comparable analytical narrative for the Task 6 experiment
and documented the source script separately in SOURCE_SCRIPT.md.

## Tool Used

Platform: ElevenLabs
Model: Eleven v4
Voice: Roger - Laid-Back, Casual, Resonant

No real individual's voice was cloned.

## Experiment

### Attempt 1

- Stability: 50%
- Similarity: 75%
- Same source script
- Same voice
- Same model
- Duration: approximately 116 seconds

Artifact:

`artifacts/attempt_01_AI_GENERATED.mp3`

### Attempt 2

- Stability: 70%
- Similarity: 50%
- Same source script
- Same voice
- Same model
- Duration: approximately 116 seconds

Artifact:

`artifacts/attempt_02_AI_GENERATED.mp3`

Keeping the source content and voice constant allowed the experiment to
focus on how changes in generation settings affected synthetic speech.

## Detection Experiment

I uploaded Attempt 2 to AI Voice Detector.

The detector classified the recording as AI generated with an overall
AI score of 96%.

It analyzed 19 audio segments, and all 19 were classified as AI
generated.

The screenshot is included at:

`screenshots/detection_attempt_02_AI_GENERATED.png`

More information is available in DETECTION_PROVENANCE.md.

## Repository Contents

`SOURCE_SCRIPT.md`
- Exact source narrative used for generation.

`PROCESS_LOG.md`
- Tools, settings, iterations, screenshots, timing, and observations.

`EVALUATION.md`
- Critical assessment of both synthetic audio attempts.

`DETECTION_PROVENANCE.md`
- AI audio detector and provenance findings.

`artifacts/`
- Synthetic audio files.

`screenshots/`
- ElevenLabs settings and detector result.

## Reproducing the Experiment

1. Open ElevenLabs Text to Speech.
2. Select the Eleven v4 model.
3. Select the Roger - Laid-Back, Casual, Resonant voice.
4. Copy the script from SOURCE_SCRIPT.md.
5. Generate Attempt 1 using the documented settings in PROCESS_LOG.md.
6. Generate Attempt 2 using the second set of documented settings.
7. Export both artifacts with filenames clearly identifying them as
   AI-generated.
8. Compare the audio using the evaluation criteria documented in
   EVALUATION.md.

Results may vary as web-based AI models and tools are updated over time.

## What I Learned

The experiment demonstrated that the same source script and synthetic
voice can produce perceptible differences when generation parameters
are changed.

Keeping the script, model, and voice constant created a useful
controlled comparison of Stability and Similarity.

The experiment also showed that synthetic-media evaluation should not
depend only on whether speech is intelligible. Prosody, cadence,
emotional variation, pauses, and other subtle characteristics can
affect whether generated speech feels natural.

The AI audio detector correctly identified Attempt 2 as synthetically
generated with a 96% AI score.

The broader lesson is that creating synthetic speech is increasingly
accessible, while responsible use still depends on explicit disclosure,
careful documentation, and awareness of provenance.

## Ethical Safeguards

- No identifiable real person's voice was cloned.
- A generic ElevenLabs synthetic voice was used.
- Both artifact filenames explicitly contain `AI_GENERATED`.
- The audio includes a spoken synthetic-media disclosure.
- The repository begins with a synthetic-media disclosure.

## Academic Purpose

This repository was created solely for Research Task 6:
Constructing and Evaluating Synthetic Media.
