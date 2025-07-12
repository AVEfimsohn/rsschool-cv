# Efimenko Alexei

# Contact Information
- **Phone Number:** +375297777777
- **Email:** kumyo5500@gmail.com
- **GitHub:** [AVEfimsohn](https://github.com/AVEfimsohn)
- **Telegram:** [@EOStridsvagn](t.me/EOStridswagn)

# About me
Hi, I'm a second year student of BNTU, [Faculty of Information Technology and Robotics](https://bntu.by/en/faculties/fitr). Over the past year, I've got accuaited with 
basics of algorithmisation, computer architecture, math and learned basics of different programming languages like Python, C++ and TurboAssembler.
Beyond university, I’m passionate about expanding my skills by taking specialized courses on [Stepik](https://stepik.org/users/913765513/profile)
and [leetcoding](https://leetcode.com/u/senjorhilter/).

# Skills
- Python(TKinter, Matplotlib)
- C++(C++17, Qt framework)
- TurboAssembler(simple stuff under [DosBox](https://en.wikipedia.org/wiki/DOSBox))

# Code Examples
Python code from my lab work that encrypts text in certain file by adding 5 to symbol code:
```python
input_filename = input("Enter input filename: ")
output_filename = input("Enter output filename: ")

with open(input_filename, 'rb') as input_file:
    data = input_file.read()

encoded_data = bytes((byte + 5) % 256 for byte in data)

with open(output_filename, 'wb') as output_file:
    output_file.write(encoded_data)

print(f"File '{input_filename}' has been encoded and saved as '{output_filename}'.")
```

# Education
Right now I'm pursuing Bachelor degree in Software Engineering at BNTU's Faculty of Information Technology and Robotics.
Apart from that I opt for various stepik cources:
https://stepik.org/cert/2549867
https://stepik.org/cert/2544933
https://stepik.org/cert/2497089

# Languages
- Russian
- Belarusian
- English
