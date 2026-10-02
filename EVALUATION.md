# Critical Evaluation

## Evaluation Approach

For this experiment, I generated two synthetic-audio versions of the same analytical script using ElevenLabs. I kept the **script, voice, and model unchanged** between the two attempts and changed the **Stability and Similarity settings**.

This created a controlled comparison in which the main question was whether changing these settings noticeably affected the naturalness, consistency, pacing, and overall delivery of the synthetic voice.

Both files were also compared for duration, pauses, and broad pitch characteristics.

---

## Attempt 1

**Artifact:** `attempt_01_AI_GENERATED.mp3`

**Approximate duration:** 116.27 seconds

Attempt 1 served as my baseline. Overall, the voice was clear and easy to understand. The pronunciation of the sports-analysis terminology was consistent, and the synthetic narrator delivered the complete script without skipping content or introducing noticeable verbal errors.

One of the stronger aspects of this attempt was that the narration sounded polished enough to function as professional automated narration. The voice maintained a consistent volume and speaking style across the recording.

However, there were still cues that made the recording feel synthetic rather than like spontaneous human speech. The cadence was highly controlled, and there was little natural hesitation or conversational uncertainty. A human speaker explaining an analytical recommendation would normally vary their timing more strongly around important conclusions or occasionally introduce small pauses, breaths, or changes in emphasis.

The audio contained approximately **15 noticeable pauses longer than 0.25 seconds**, totaling about **8.23 seconds**. This gave Attempt 1 slightly more pause time than Attempt 2.

The estimated median pitch was approximately **124 Hz**, and overall pitch variability was very similar to Attempt 2. This suggests that the setting changes did not produce a dramatic global difference in pitch or intonation.

### What worked

- Clear pronunciation and intelligibility
- Consistent volume and delivery
- Complete delivery of the source script
- Appropriate pacing for an analytical narration
- Synthetic-media disclosure was clearly spoken at the beginning
- The voice was convincing enough to work as polished automated narration

### What felt synthetic

- Very controlled cadence
- Limited conversational hesitation
- Lack of natural breathing patterns
- Some sentences felt more like prepared narration than spontaneous explanation
- Emotional emphasis remained relatively restrained even when the script reached its main recommendation

### Would I be fooled?

If I knew nothing about the source, I could initially accept this as professionally produced narration. However, after listening carefully, the regular cadence and controlled delivery would make me suspicious that it was generated or heavily processed.

Someone who does not regularly work with synthetic-audio tools might be more likely to accept it as a human voice, especially if the explicit disclosure at the beginning were removed.

---

## Attempt 2

**Artifact:** `attempt_02_AI_GENERATED.mp3`

**Approximate duration:** 115.96 seconds

For Attempt 2, I changed the Stability and Similarity settings while keeping everything else constant.

The most important finding was that the resulting recording was **not dramatically different** from Attempt 1. Both recordings had nearly identical total durations, with only about **0.31 seconds** separating them.

Attempt 2 was slightly tighter in its pacing. Like Attempt 1, it contained approximately **15 pauses longer than 0.25 seconds**, but the total pause duration was approximately **7.60 seconds**, compared with approximately 8.23 seconds in Attempt 1.

This means Attempt 2 spent roughly **0.6 seconds less time in longer pauses** despite delivering the same script.

The estimated median pitch was approximately **122 Hz**, compared with approximately 124 Hz in Attempt 1. Pitch variability was almost identical across both files. This was an interesting result because I expected changing the generation settings to create a more obvious overall acoustic difference.

The second attempt felt slightly more controlled and consistent in its delivery. The transitions between sentences were somewhat tighter, although it still retained many of the same synthetic characteristics as Attempt 1.

### What worked

- Clear and consistent speech
- Complete delivery of the identical source material
- Slightly tighter pacing
- Consistent pronunciation throughout the recording
- Stable delivery across a relatively long piece of narration

### What felt synthetic

- The delivery remained very controlled
- Natural breathing was limited
- Emotional emphasis remained subtle
- The voice rarely sounded as if it were spontaneously thinking through the recommendation
- Some longer analytical sentences retained a text-to-speech quality

### Would I be fooled?

Like Attempt 1, this version could probably pass as polished narration to a casual listener for at least part of the recording. However, an attentive listener would likely notice the unusually consistent rhythm and lack of ordinary conversational imperfections.

---

## Attempt 1 vs. Attempt 2

The most interesting result of the experiment was how **similar the two outputs remained despite changing Stability and Similarity**.

| Characteristic | Attempt 1 | Attempt 2 |
|---|---:|---:|
| Duration | 116.27 sec | 115.96 sec |
| Longer pauses detected | 15 | 15 |
| Total longer-pause time | 8.23 sec | 7.60 sec |
| Median estimated pitch | ~124 Hz | ~122 Hz |
| Overall pitch variability | Very similar | Very similar |

Attempt 1 contained slightly more pause time, while Attempt 2 delivered the same content somewhat more tightly. However, the global pitch characteristics and overall duration remained extremely close.

This was useful because it showed that adjusting Stability and Similarity does not necessarily transform the recording dramatically. The changes can instead appear in more subtle characteristics such as consistency, phrasing, micro-pauses, and how strongly the output maintains the character of the selected voice.

Of the two, **Attempt 2 felt slightly more controlled and consistent**, while **Attempt 1 allowed slightly more space in the delivery**. Neither attempt completely eliminated the cues of synthetic speech.

I would therefore not describe one attempt as dramatically superior to the other. Instead, the second attempt demonstrated that parameter changes can refine the behavior of the voice without fundamentally changing the overall character of the generated narration.

---

## Most Noticeable Synthetic-Media Failure Modes

The most noticeable synthetic characteristics across both attempts were:

1. **Cadence** — Speech remained unusually consistent for a long analytical explanation.
2. **Breathing** — The recordings lacked some of the breathing and small vocal interruptions that normally occur in natural speech.
3. **Emotional register** — Important analytical conclusions were delivered clearly, but without the degree of spontaneous emphasis a human speaker might naturally introduce.
4. **Conversational variation** — There were few hesitations, corrections, or irregularities.
5. **Prosody** — Although pitch changed throughout the speech, the overall delivery remained highly controlled.

Interestingly, neither recording contained an obvious catastrophic failure. There were no major pronunciation breakdowns, missing sections, or severe audio artifacts. The weaknesses were therefore mostly **subtle cues of artificiality rather than obvious errors**.

---

## Safety Filters and Refusals

I did not encounter any safety refusal during either attempt.

Both recordings used a generic synthetic voice provided by ElevenLabs rather than cloning or imitating the voice of a real identifiable person. The script consisted of an academic sports-analysis narrative and included an explicit synthetic-media disclosure.

ElevenLabs generated the complete script in both cases without refusing or noticeably degrading any portion of the content.

---

## Connection to the Detection Experiment

My subjective evaluation suggested that the recordings were convincing as automated narration but still contained detectable characteristics of synthetic speech.

This was consistent with the separate AI-audio detection experiment. When Attempt 2 was analyzed using AI Voice Detector, the detector classified it as **AI Generated with a 96% AI score**, and all **19 analyzed segments** were classified as AI-generated.

This was particularly interesting because the audio could sound polished to a casual listener while still containing enough acoustic characteristics for the detector to classify it with high confidence.

---

## Final Reflection

Before conducting the experiment, I expected changing Stability and Similarity to create a much more obvious difference between the two recordings. Instead, the differences were comparatively subtle.

Keeping the script, voice, and model constant showed that the settings influence the behavior of the generated speech, but they do not necessarily transform its overall acoustic character.

The experiment also changed how I think about the idea of a synthetic voice being “convincing.” A recording does not need to be indistinguishable from human speech to be useful or persuasive. Both attempts were clear enough to communicate the analytical argument effectively.

At the same time, careful listening revealed characteristics that still separated the generated narration from spontaneous human speech: regular cadence, limited breathing, restrained emotional variation, and a lack of natural conversational imperfections.

My main conclusion is that **synthetic speech can already be convincing as polished narration without being completely convincing as spontaneous human speech**. The distinction becomes especially important when considering how the same technology could be used without disclosure or with the voice of a real identifiable person.
