
# Bill Splitter 💸

This Python program simplifies splitting a bill among friends, with an optional "Who is lucky?" feature to make one participant exempt from paying.

---

## 🚀 Features

- **Even Bill Splitting**: Splits the total bill evenly among all participants.
- **"Who is lucky?" Feature**: Randomly selects one participant to be exempt from paying.
- **Interactive Input**: Allows participants' names and bill details to be entered interactively.

---

## 🛠️ How to Use

1. **Run the Program**  
   Execute the script using Python:
   ```bash
   python bill_splitter.py
   ```

2. **Follow the Prompts**  
   - Enter the number of friends joining (including yourself).
   - Provide the names of all participants.
   - Enter the total bill value.
   - Decide whether to use the "Who is lucky?" feature.

3. **View Results**  
   The program will display the split amounts for each participant.

---

## 📖 Example Usage

### Input
```
Enter the number of friends joining (including you):
3
Enter the name of every friend (including you), each on a new line:
> Alice
> Bob
> Charlie
Enter the total bill value:
120
Do you want to use the "Who is lucky?" feature? Write Yes/No:
Yes
```

### Output
```
Charlie is the lucky one!
{'Alice': 60.0, 'Bob': 60.0, 'Charlie': 0}
```

---

## 📂 Project Structure

```
bill_splitter_project/
├── bill_splitter.py  # Main Python script
├── README.md         # Documentation
├── LICENSE           # Apache 2.0 License
```

---

## 🛠️ Requirements

- Python 3.x

---

## 📬 Contributing

Contributions are welcome! If you find any issues or have ideas for new features, feel free to create an issue or submit a pull request.

---

## 📜 License

This project is licensed under the Apache 2.0 License. See the [LICENSE](LICENSE) file for details.

---

### Thank you for using the Bill Splitter! 😊
