# Reframe: Anti-Sycophantic AI Advice Prototype

## Project Status

Reframe is a high-fidelity, seven-screen Figma prototype that explores how an AI advisor can provide emotional support without automatically agreeing with the user.

**Implemented**
- Seven connected interface states.
- Normal empathy and reframing flow.
- Failure and user-triggered recovery flow.
- User-selected support and action-planning states.

**Simulated**
- LLM responses are implemented through predefined states.
- Tone checking and recovery behaviour are simulated for demonstration.

**Planned**
- Live LLM integration.
- Dynamic tone classification.
- Long-term memory and personalised communication preferences.

## Technology Stack

- **Figma:** Interface design, component layout and prototype flow.
- **OpenAI ChatGPT/Codex:** Assistance with design ideation, interface copy, report structure and code-based image preparation.
- **Excalidraw:** System architecture diagram.
- **Markdown/GitHub:** Project documentation and submission evidence.

No live LLM API is connected. No API keys are included in this repository.

## Running or Inspecting the Work

- **Figma prototype:** [Click here to view the interactive prototype](https://www.figma.com/design/KvErqFrDckmQZ1TUNsTNXL/Untitled?node-id=4-53&t=J1Nr4JEQP702brGY-1)
- **System diagram:** [`diagrams/system_architecture.png`](diagrams/system_architecture.png)
- **UI screenshots:** see `screen1.png` through `screen7.png`.

To inspect the interaction, open the Figma prototype and follow this path:

1. Enter a situation and select an emotion tag.
2. Review the Objective Empathy response.
3. Continue to the Grounded Reframe.
4. Select “Try a different angle” to inspect the simulated failure flow.
5. Use “Too harsh, rephrase” to trigger the recovery state.
6. Choose the preferred form of support and inspect the resulting next step.

## Development Record

- **Phase 1 - Initial concept:** A five-screen flow covering emotional input, empathy, perspective-taking and action planning.
- **Phase 2 - Failure and recovery:** The prototype was extended to seven screens after identifying that an anti-sycophantic system could overcorrect and become overly critical. Screen 4 exposes the failed tone check, while Screen 5 provides a user-triggered rephrasing and recovery path.
- **Phase 3 - User control:** Direct advice was replaced with a support-choice menu on Screen 6. This lets users request another perspective, prepare a response or simply be heard.
- **Phase 4 - Visual refinement:** The final pass standardised colours, type hierarchy, progress indicators, figure captions and the sequence of the seven exported screens. I checked that the normal and failure paths reconnect before the support-choice and action-planning stages.

## AI Assistance

- **Design ideation and prototyping support:** I used OpenAI ChatGPT/Codex to help develop the seven-screen flow, explore interface layouts, generate implementation-ready screen visuals and refine written copy.
- **Report support:** AI tools were used to suggest report structure, figure captions, language improvements and possible references. I reviewed all suggestions rather than submitting them unchecked.
- **Verification:** I checked that the written descriptions match the Figma screens, that the normal and failure branches are clearly distinguishable, and that all cited works correspond to the references listed in the report.
- **Control:** I selected and edited the final design, content and references presented in this repository.

## Evaluation Scope

This submission demonstrates an interaction concept and simulated AI behaviour. It does not report a live model evaluation or a completed user study.
