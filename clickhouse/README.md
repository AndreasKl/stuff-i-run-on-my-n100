## generate a password

echo -n "password" | sha1sum | tr -d '-' | xxd -r -p | sha1sum | tr -d '-'