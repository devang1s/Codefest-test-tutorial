'''
Imports

Import statement:
pip install google-generativeai
'''

import google.generativeai as genai

'''
Initialisation
'''

genai.configure(api_key=GENAI_KEY)
model = genai.GenerativeModel(model_name='gemini-2.5-flash')
chat_history = []
chat = model.start_chat(history=chat_history)

'''
Generate the AI response
'''

def generate_response(prompt):

    # Add prompt to chat history
    # .txt addition to be added...
        
    # Generate and add response to history
    try:
        response = chat.send_message(prompt)
    except:
        print()
    
    # Refer to line 72...
    try:
        return response.text
    except:
        print(end='')
