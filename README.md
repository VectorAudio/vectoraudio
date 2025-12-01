# Vector Audio™

**Vector Audio™** is a proposed next-generation, model-based audio standard designed to move beyond static waveform formats. Instead of storing fixed PCM samples, Vector Audio represents performances, instrument and vocal models, and scenes in a way that can be rendered in real time and upgraded as technology advances.

This repository hosts:

- The public-facing website for **vectoraudio.net**
- Drafts of the **Vector Audio Specification (VASP)**
- Links and resources for contributors, researchers, and industry partners

---

## What is Vector Audio?

Vector Audio is a **model-based audio framework**. Instead of recording a single, frozen version of audio, VA stores:

- **Performance data** (VAP) – timing, expression, pitch curves, gestures  
- **Instrument and vocal models** (VAM / VAD) – how sounds are generated  
- **Scenes and spatial info** (VAS) – where sounds live in space  

At playback time, a render engine (VARE) produces the final audio in real time, adapting to devices, rooms, and listener preferences. As models and render engines improve, existing Vector Audio content can sound better without being re-recorded or remastered.

---

## Spec Drafts

- **VASP v0.1 (Draft)** – `docs/vasp-spec-0.1.md` (work in progress)

Future versions will include additional formats (VAR, VAM, VAD, VAX, etc.) and conformance guidance.

---

## Get Involved

If you are:

- An audio developer  
- A DAW, plugin, or hardware manufacturer  
- A researcher in DSP, ML, or acoustics  
- A musician, producer, or audio engineer

…and you’re interested in helping shape Vector Audio, please send a brief message with your background to:

**info@vectoraudio.net**

---

## Trademark

**Vector Audio™** is a pending trademark in the United States. All references to Vector Audio™ in this repository and the accompanying website refer to the proposed model-based audio standard and related specifications.

Nothing in this repository constitutes legal advice.
