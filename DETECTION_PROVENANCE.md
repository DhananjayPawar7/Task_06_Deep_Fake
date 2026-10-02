# Detection and Provenance

## AI Audio Detection Experiment

Artifact tested:

`artifacts/attempt_02_AI_GENERATED.mp3`

Detector:

AI Voice Detector
(aivoicedetector.com)

## Result

The detector classified the recording as:

**AI Generated**

Reported AI score:
**96%**

Maximum segment score:
**99%**

Average score:
**96%**

Segments analyzed:
**19**

All 19 analyzed segments were classified as AI generated.

A screenshot of the result is stored at:

`screenshots/detection_attempt_02_AI_GENERATED.png`

## Interpretation

The detector correctly identified the ElevenLabs-generated recording as
synthetic and did so with high confidence.

This result should not be interpreted as evidence that the detector will
identify every synthetic voice accurately. It only demonstrates its
performance on this particular ElevenLabs artifact.

## Provenance Observation

The original ElevenLabs audio files also contained C2PA provenance
information indicating algorithmically generated media.

This illustrates an important difference between detection and
provenance.

Detection attempts to infer whether media is synthetic by examining the
artifact.

Provenance attempts to preserve information about where and how the
artifact was created.

## Conclusion

In this experiment, both the detector result and the original provenance
information correctly indicated that the artifact was synthetically
generated.
