# Encryptix-TASK1
def chatbot():
    print("🤖 Hello! I’m ChatBot. Type 'bye' to exit.")

    while True:
        user_input = input("You: ").lower()

        if 'hello' in user_input or 'hi' in user_input:
            print("Bot: Hi there! How can I help you?")
        elif 'how are you' in user_input:
            print("Bot: I'm just a program, but I'm functioning properly 😄")
        elif 'your name' in user_input:
            print("Bot: I’m a simple chatbot created to help you.")
        elif 'help' in user_input:
            print("Bot: Sure! I can help with general questions. Ask me anything.")
        elif 'bye' in user_input:
            print("Bot: Goodbye! Have a great day!")
            break
        else:
            print("Bot: Sorry, I didn't understand that. Can you rephrase?")

# Run the chatbot
if __name__ == "__main__":
    chatbot()
