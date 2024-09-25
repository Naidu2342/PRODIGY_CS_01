def encrypt(text, shift):
    result = ""
    for char in text:
        if char.isalpha():
            shift_amount = 65 if char.isupper() else 97
            result += chr((ord(char) + shift - shift_amount) % 26 + shift_amount)
        else:
            result += char
    return result

def decrypt(text, shift):
    return encrypt(text, -shift)

def main():
    choice = input("Type 'encrypt' to encrypt or 'decrypt' to decrypt: ").lower()
    text = input("Enter your message: ")
    shift = int(input("Enter shift value: "))

    if choice == 'encrypt':
        print("Encrypted message:", encrypt(text, shift))
    elif choice == 'decrypt':
        print("Decrypted message:", decrypt(text, shift))
    else:
        print("Invalid choice. Please type 'encrypt' or 'decrypt'.")

if __name__ == "__main__":
    main()
    
