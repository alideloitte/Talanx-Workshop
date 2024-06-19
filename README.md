# Setup Guide

### Assumptions: We Assume that following things are already installed:
- Python3.10 & Pip
- Pipenv 

**Step 1:** Run the bash script            
```
sh setup.sh  //for Mac
./setup.sh   //for Ubuntu   
```

**Step 2:** Activate virtual enviornment 
```
pipenv shell
```

**Step 3:** Export OpenAI API 
```
export OPENAI_API_KEY="Your_Key"
```

**Step 4:** Run Talanx-Workshop.py
```
streamlit run Talanx-Workshop.py
```

#### Rails Config:
- All the related Rails are in topics.co
- Off_topic.co contains some more usecase. You can use them also in topics.co and extend your application. 



