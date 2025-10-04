# indraneel-langsmith-MAT496
# Name- Indraneel Ghosh
# Roll number- 2410110146

## MODULE 1:


### Vid-1: Basics of Tracing and Metadata
- **Learnings:** Learnt the fundamentals of tracing: it's use of monitoring and analysing llm at runtime. Use of metadata in langsmith in analysing and debugging llm system.
- **Changes:** setting environment variables, adding traceable functions, making my own questions
- **My code:** https://github.com/indraneel2110/indraneel-langsmith-MAT496/blob/main/tracing_basics.ipynb

### Vid-2: Types of Run
- **Learnings:** Learnt about the different types of runs supported in Langsmith. Also learnt about difference in tracing for different run types and formatting effects on tracing outputs.
- **Changes:** enabled the tracing, made the prompts a bit different, added different question
- **My code:** https://github.com/indraneel2110/indraneel-langsmith-MAT496/blob/main/types_of_runs.ipynb

### Vid-3: Alternative Tracing Methods
- **Learnings:** Learnt different ways of enabling tracing, created by Langgraph and nodes created. Also learnt the function trace() for more granural control, also did RunTree basics on my own accord.
- **Changes:** enabled the tracing, added trace() instead of @traceable, added my own questions and altered some prompts
- **My code:** https://github.com/indraneel2110/indraneel-langsmith-MAT496/blob/main/alternative_tracing_methods.ipynb

### Vid-4: Conversational Threads
- **Learnings:** Learnt what is threading, application of metadata in creating conversational threads. Basically by having a common ID across different runs, there exists a sequence of interactions and as a result the simulation looks natural.
- **Changes:** enabled the tracing, used metadata in establishing conversational threads, added my own questions and altered some prompts
- **My code:** https://github.com/indraneel2110/indraneel-langsmith-MAT496/blob/main/conversational_threads.ipynb


## MODULE 2:


### Vid-1: Dataset Upload
- **Learnings:** Learnt how to create datasets and what's the use of datasets in Langchain: to provide referance examples to the model as to what we expect from it. Also learnt ways in which to add data in the dataset: through the UI manually, through tracing and from AI.
- **Changes:** enabled the tracing, generated my own dataset, changed the question
- **My code:** https://github.com/indraneel2110/indraneel-langsmith-MAT496/blob/main/dataset_upload.ipynb

### Vid-2: Evaluators
- **Learnings:** Learnt about evaluators, which are basically tools that measure and tell us how good the performance of the model is through a qualitative score. Also learnt how to define evaluators through different modes: in local code, through LLM as judge and through UI.
- **Changes:** enabled the tracing, edited the prompt (since we already did low score for least similar output, I did a completely opposite prompt to get a high 9
- **My code:** https://github.com/indraneel2110/indraneel-langsmith-MAT496/blob/main/evaluators.ipynb
