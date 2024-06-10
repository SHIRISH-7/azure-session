# Chat with Multiple documents
1. Prerequisites
    1. Anaconda:- https://www.anaconda.com/download
    2. VS Code
        1. Jupyter Extension
        2. Python Extension
2. Create an env
For this case we will be using name ```session_env```, feel free to use different name
    ```
    conda create --name session_env -y 
    ```
    
3. Activate your environment
    ```
    conda activate session_env
    ```
4.  Install requirements.txt
    ```
    pip install -r requirements.txt
    ```
5. Run the streamlit server with file name for example if ```app.py``` is your file name then:
    ```
    streamlit run app.py
    ```