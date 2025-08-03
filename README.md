# Browser-AI-Agent-using-LLM-Model-Playwright-Browser-Use-Web-UI
Browser AI Agent using any LLM Model + Playwright + Browser-Use + Web-UI(Control your browser with AI assistance)

🌐 Browser Use WebUI - Control your browser with AI assistance

Important url:
      https://github.com/browser-use/browser-use
      https://github.com/browser-use/web-ui
      https://docs.astral.sh/uv/#highlights
      https://aistudio.google.com/apikey
      http://127.0.0.1:7788


Step 1:
**[cmd]** Install python

Step 2:
Enable AI to control your browser 🤖
**[go here]** https://github.com/browser-use/browser-use
**[cmd]** pip install browser-use

      - If get and error then add this --break-system-packages 
      - **[cmd]** pip install browser-use --break-system-packages [if face any issue]

Step 3:
**[cmd]** playwright install 
**[cmd]** playwright install chromium --with-deps --no-shell


Step 4:
Create folder in your local where you want to clone repository
Go in cmd and go to path where you create folder like [D:\Manoj kumar\ai-project\web-ai-agent]

**[go here]** https://github.com/browser-use/web-ui  - Read documents if you want more details

**[cmd]** git clone https://github.com/browser-use/web-ui.git 
**[cmd]** cd web-ui 

Step 5:
An extremely fast Python package and project manager, written in Rust
**[go here]** https://docs.astral.sh/uv/#highlights - and find below query and read the documents
**[powershell]** powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex" 


Step 6: Set Up Python Environment
After executed above command then must be needed to set Environment path in you system as well in path dir
**[cmd]** uv venv --python 3.11 

Step 7: Activate the virtual environment:
**[cmd]** .venv\Scripts\activate


Step 8: Install Dependencies
**[cmd]** uv pip install -r requirements.txt
 
Step 9: Install Browsers in playwright.
**[cmd]** playwright install --with-deps


Or you can install specific browsers by running:
**[cmd]** playwright install chromium --with-deps

Step 4: Configure Environment
**[cmd]** copy .env.example .env - **skip for now**

Step 5: Enjoy the web-ui
**[cmd]** python webui.py --ip 127.0.0.1 --port 7788

**Getting issue like browser not match with the docker then follow below steps**
You should check browser-use version 
Step1: **[cmd]** pip show browser-use - check browser-use: version

Step2: go to folder then check **environment.txt** file - check browser-use: version as well
If both are not matched then follow below steps
**[cmd]**  pip uninstall browser-use
**[cmd]**  pip install browser-use==0.1.48
**[cmd]**  python webui.py --ip 127.0.0.1 --port 7788

**After server is started then go flow below steps**
Step 1: Access the WebUI: 
Open your web browser and navigate to **http://127.0.0.1:7788**


- Then you will see **Browser Use WebUI** interface 
- GO to LLM
- Enter google/Gemini in LLM Provider
- Need API for Control your browser with AI assistance below is the steps for get api key

**CREATE GEMINI API KEY [OPEN SOURCE]**
- Search on google → GEMINI API KEY -
- Direct go if already login - https://aistudio.google.com/apikey
- Click on → Create API key
- Click on → create new api
- You will get something like this → A234234kasdkfjhskajfjah2l2lTFASzHoAXasdfasdE

**Go to this url http://127.0.0.1:7788/?__theme=dark**
- Agent-setting
  - LLM Provide
    - Enter Google
      - Gemini-2.0-flash
      - In Api key [paste here create api key]
      
- Disable the security in browser setting

**YOU ARE READY NOW FOR AI AGENT SETUP**
- Go to run agent
- Enter what you want to perform and explore
- example:
    - Open the google.com
    - search naukri.com
    - Scroll the page
    - close the browser  

**Once setup is done then when you want do this again then you should only below setups** 
- Open a terminal (CMD or PowerShell).
- go into your project directory:
    - like: cd "D:\Manoj kumar\ai-project\web-ai-agent\web-ui"
- Activate your virtual environment
    - **[cmd]** .venv\Scripts\activate
- Start the web UI
    -**[cmd]** python webui.py --ip 127.0.0.1 --port 7788

**ENJOY Control your browser with AI assistance**
