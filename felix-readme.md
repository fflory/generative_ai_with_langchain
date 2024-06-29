bought with kindle felix.flory@gmail.com

pdf is at https://1drv.ms/b/s!AhUtYe0GtfSGg59LMLYpGrzohfFVgg?e=BPjeYQ


    conda env create --file langchain_ai.yaml
    conda activate langchain_ai

https://github.com/benman1/generative_ai_with_langchain


    import os 
    from getpass import getpass

    print("enter your openai api key")
    os.environ["OPENAI_API_KEY"] = getpass()


my config.py file to get secret keys

    import os
    OPENAI_API_KEY=os.environ["OPENAI_API_KEY"]
