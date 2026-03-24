---
layout: page
title: Projects
permalink: /projects/
---

## RESCUE MATE
*House of Computing and Data Science, Hamburg* · [rescue-mate.de](https://rescue-mate.de)

RESCUE MATE is a federally funded R&D project bringing together 11 institutional partners to build real-time situational awareness tools for emergency responders, with a focus on flood and storm surge scenarios in Hamburg.

My contribution focused on the NLP components: the system analyses social media streams and other text sources in real time to detect and structure crisis-relevant information. This includes automatic speech recognition pipelines to transcribe emergency radio communication, and NLP models for event extraction and classification. The project also includes an interactive crisis map that visualises AI-extracted, geoparsed events through a knowledge graph backend.

The map is powered by an end-to-end AI pipeline: posts and news streams are continuously monitored, and events are automatically identified using large language models. Each event is classified for crisis relevancy and geoparsed — LLMs resolve location mentions to precise geographic coordinates. The structured event data is ingested into a knowledge graph that captures relationships between events, locations, and entities. At query time, the map retrieves and renders this information in real time, giving emergency responders a live, structured view of unfolding situations across a region.

<a href="https://map.skynet.coypu.org" class="demo-btn" target="_blank" rel="noopener">Open Crisis Map Demo</a>

> **Note:** The live demo runs on synthetic data — real-world crisis data is operationally sensitive and not publicly exposed. The demo is also not always running and may be temporarily unavailable.

---

## DZHK — Clinical Information Extraction
*University of Hamburg · in collaboration with UKE*

A collaboration with the Universitätsklinikum Hamburg-Eppendorf (UKE) focused on extracting structured information from Arztbriefe — German clinical discharge letters. I designed and implemented NLP pipelines to identify and structure clinically relevant information from unstructured medical free text, enabling downstream research workflows that would otherwise require manual annotation.

---

## SPEAKER
*Fraunhofer IAIS, Dresden* · [speaker.fraunhofer.de](https://www.speaker.fraunhofer.de)

SPEAKER is a modular B2B voice assistant platform developed by Fraunhofer IAIS and IIS, offering European companies a sovereign, GDPR-compliant alternative to overseas voice assistants. It combines speech recognition, natural language understanding, and dialogue management into a scalable system deployed across industries including maintenance, law enforcement, and transportation.

I was a core contributor to the design and implementation of the dialogue design framework — the core architecture governing how conversations flow, how user intents are resolved across turns, and how the system navigates complex task-oriented interactions. I also built NLU components for intent recognition and entity extraction, and trained ML models for dialogue understanding and response selection.
