# Zeigler Folder
We sincerely thank NASSM and the Journal of Sport Management (JSM) for making these articles publicly available. The original articles can be accessed directly from the [JSM homepage](https://journals.humankinetics.com/view/journals/jsm/jsm-overview.xml).

The `Zeigler` folder contains 33 publicly available Zeigler Award lectures published in JSM. Each article is available in PDF, Markdown, and JSON formats to facilitate verification, preprocessing, and NLP analysis. Note that Dr. Damon Andrew's lecture has not yet been published in JSM. Neverthless, we transcribed his speech, delivered at this year's (2025) award reception, and included the transcript in the `2025` folder under `Zeigler` for analysis.

# SystemPrompt Folder
The `SystemPrompt` folder contains the exact system prompts (Research Assistant and Supervisor) utilized during our experiments. These prompts can help users replicate or experiment with our analyses to verify findings or extend our methodology.

# Experiment Instructions
1. Go to [Google AI Studio](https://aistudio.google.com).
2. Select the `Gemini 2.5 Pro Preview` model.
3. Set `Temperature` to 1.
4. Choose `Structured Output` under `Tools`.
5. Use the system prompts provided in the `SystemPrompt` folder to configure `System Instructions`.
6. Upload a Zeigler lecture from the `Zeigler` folder, preferably in Markdown or JSON format.
7. Hit `Run`.
