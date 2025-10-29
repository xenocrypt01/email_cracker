

```bash
git clone https://github.com/xenocrypt01/email_cracker.git
cd email_cracker
```
## **Configure the Tool (config.ini)**

The tool requires the configuration of the `config.ini` file before use. The configuration file allows you to specify the email provider's host and port.

The default configuration in `config.ini` is set up for Gmail, but you can modify these settings to test other email providers (such as Yahoo, Outlook, etc.).

### **Example config.ini for Gmail:**

```ini
[SMTP]
host = smtp.gmail.com
port = 587
```

If you're testing with a different provider, replace the host and port with the appropriate values.

<!-- ## Install Dependencies

If you haven't already, you can install all the necessary Python dependencies: -->

## **Run the Tool**

After configuring the config.ini file, run the tool:  <!-- by passing in the target email address: -->
```bash
python3 cracker.py
```
