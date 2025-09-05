def count_characters(text):
    return {char: text.count(char) for char in set(texT)}

if __name__ == "__main__":
    sample = "commit"
    print(f"Character counts: {count_characters(sample)}")
