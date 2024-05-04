# SMTPClientProtocolParser
This Python script creates an SMTP client to send emails with attachments. It validates sender and receiver email addresses, prompts for attachment file path and email body, encodes attachments, constructs MIME multipart/mixed header, and sends the email.


This Python script establishes an SMTP client allowing users to send emails with attachments. It first imports necessary modules—`socket` for networking, `re` for regex, and `base64` for encoding. Then, it defines a regex pattern for email validation and sets up connection parameters for the SMTP server. The script prompts users for sender and receiver email addresses, validates them, and sends SMTP commands. Next, it prompts for attachment file path and email body. If an attachment is provided, it's encoded using base64. The script constructs the email header with MIME multipart/mixed content type and sends the email with attachment to the SMTP server. Finally, it offers the option to quit.
