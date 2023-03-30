# ASP_yoruba

We are solving a speech recognition problem for the Yoruba language.
As promising models for training , the following were considered:

facebook/wav2vec2-xls-r-300m
openai/whisper-small

We use datasets for training:
google/fleurs
tobiolatunji/afrispeech-200
mozilla-foundation/common_voice_12_0

WER (Word error rate) is used as the main evaluation metric.

WER:

1. 67.8866
dataset: google/fleurs
Model: openai/whisper-small
Source: https://huggingface.co/steja/whisper-small-yoruba

2. 57.8640
dataset: google/fleurs + mozilla-foundation/common_voice_12_0
Model: facebook/wav2vec2-xls-r-300m
