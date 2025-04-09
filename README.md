# dbkeys

> Helper tool for easy management of configuration files and keys that go along with each file.

## 📄 Description

This script is a tool I wrote to assist with my tasks of updating configuration files and configuration keys in database patches. I need to keep track of configuration files and their corresponding keys that allow each file to be highly customizable by the user. 
Python dictionaries are the perfect solution for this task. A quick script can easily associate file names (keys) to their corresponding config keys (values). 
The result is a string of keys that are single quoted, comma separated, and alphabetized for easy addition to a db patch.

## 🛠️ Requirements

- Python 3.x

## 🚀 Usage

```bash
# Make sure it's executable
chmod +x dbkeys

# Run the script
./dbkeys [options]

# Or with Python directly
python dbkeys [options]
