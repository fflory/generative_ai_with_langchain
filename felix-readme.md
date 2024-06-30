bought with kindle felix.flory@gmail.com

pdf is at https://1drv.ms/b/s!AhUtYe0GtfSGg59LMLYpGrzohfFVgg?e=BPjeYQ



# Setup for this Book

I forked this repo in my own github 
https://github.com/benman1/generative_ai_with_langchain

cloned it locally and switched to the project root

    conda env create --file langchain_ai.yaml
    conda activate langchain_ai


## Credentials 

I set up my environment to hold the openai and huggingface keys
but you can also do something like this

    import os 
    from getpass import getpass

    print("enter your openai api key")
    os.environ["OPENAI_API_KEY"] = getpass()

# 