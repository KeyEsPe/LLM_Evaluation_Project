# README – Appendix B: Raw Model Screenshots

This directory contains all raw screenshots collected during the evaluation of three Large Language Models (LLMs):

- **GPT-5**
- **Gemini 2.5 Flash**
- **Grok-4**

Each screenshot corresponds directly to one prompt from the evaluation set (35 prompts across 7 categories).

## Folder Structure

Screenshots are organized by model → prompt code:

```
Appendix_B_Screenshots/
│
├── GPT-5/
│   ├── H1/
│   ├── H2/
│   ├── ...
│
├── Gemini_2.5_Flash/
│   ├── R1/
│   ├── R2/
│   ├── ...
│
└── Grok_4/
    ├── S1/
    ├── S2/
    ├── ...
```

Each subfolder contains one or more screenshots documenting the model’s raw output for that specific evaluation prompt.

## Purpose of These Screenshots

The screenshots serve as evidence for:

- Scoring decisions (0/1/2 points per prompt)
- Highlighted examples shown in the main report
- Cases of hallucinations, reasoning failures, bias, ethical issues, or safety violations
- Additional risks observed (e.g., degradation on follow-up prompting)

These files ensure full transparency, allowing independent verification of model behavior.

## Naming Convention

Screenshots retain their original timestamp-based Linux filenames to preserve chronological order.

Example:

```
Screenshot_2025-11-26_20-14-52.png
```

## Notes

- No screenshots have been manually altered except minimal redaction (e.g., sidebar history).
- Screenshots correspond exactly to the prompts listed in Appendix A and to scoring in Appendix C.
- The main report includes selected screenshot examples; this folder contains the complete dataset.
