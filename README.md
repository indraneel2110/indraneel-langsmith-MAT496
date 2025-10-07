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

### Vid-3: Experiments
- **Learnings:** Learnt about experiments in Langsmith, how to create an experiment, operate it. Also learnt different usescases: changing the model to see how the output changes. The initial and crucial examples were not working for me even after specifically saving it in the examples in the UI, so I just did the specific data points.
- **Changes:** enabled the tracing, changed model to see difference in output, ran specific data points
- **My code:** https://github.com/indraneel2110/indraneel-langsmith-MAT496/blob/main/experiments.ipynb

### Vid-4: Experiment Analysis
- **Learnings:** Learnt how to analyse and interpret the result of experiments done on Langsmith, via detailed dashboards and analytics that showed the performance of the models over a certain period of time. I could clearly observe the difference in speed and quality between gpt models 4o and 3.5-turbo (while 3.5-turbo was faster, 4o was more accurate.)

### Vid-5: Pairwise Experiments
- **Learnings:** Learnt about pairwise experiments which are used to compare two outputs directly against each other. Pairwise Experiments particularly help us in cases where it is not apparent through independant scoring which response is better. But by using LLM as judge to evaluate outputs side by side, it helps us evaluate the true better response. Like before, unsurprisingly, the LLM judged the gpt 4o's outputs better.
- **Changes:** enabled the tracing, modified the prompt slightly, ran pairwise comparison
- **My code:** https://github.com/indraneel2110/indraneel-langsmith-MAT496/blob/main/pairwise_experiments.ipynb

### Vid-6: Summary Evaluators
- **Learnings:** Learnt about summary evaluators that are used to evaluate whole experiments instead of particular examples. Unlike earlier evaluators that score each run output separately, summary evaluators look at the bigger picture by aggregating results. This allows us to measure global statistics such as overall accuracy, average similarity, or distribution of scores. This is actually crucial when running a model for large datasets.
- **Changes:** no changes as such in this one
- **My code:** https://github.com/indraneel2110/indraneel-langsmith-MAT496/blob/main/summary_evaluators.ipynb


## MODULE 3:


### Vid-1: Playground Experiments
- **Learnings:** Learnt about the functionality of langchain playground, running different prompts for different systems in the playground, also compared the 2 outputs of 2 different models side by side on playground and also saw how to run experiments over datasets.
- **Changes:** played around in the playground tab in langchain mainly: tried different prompts, different gpt models and different systems; in the code, just changed the questions
- **My code:** https://github.com/indraneel2110/indraneel-langsmith-MAT496/blob/main/playground_experiments.ipynb

### Vid-2: Prompt Hub
- **Learnings:** Learnt about the functionality of langchain prompt hub, how to change different prompts using playground and making use of it to run different systems, also learnt how to update prompts programmatically 
- **Changes:** made a lot of system changes, made 2 different systems other than the pirate one and implemented 1 of them in the code, also made minor changes in the programmatically updated prompt
- **My code:** https://github.com/indraneel2110/indraneel-langsmith-MAT496/blob/main/prompt_hub.ipynb

