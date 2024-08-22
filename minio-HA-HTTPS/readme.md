# Change certifications

Go into `certs` folders and replace the dummy `private.key` key and `public.crt` files with your key and certificate.

# Set your domain name
edit the `nginx.conf` file and change the `your-domain.com` lines with the desired domain name.

# Access MinIo
The MinIO client and console will now be accessible via  domain.com and https://your-domain.com:9001.
username `admin` and password `admin`