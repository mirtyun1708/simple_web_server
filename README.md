# EX01 Developing a Simple Webserver
```
NAME:MIRTYUNJAY S
REG NO:24013065
```


# AIM:
To develop a simple webserver to serve html pages and display the configuration details of laptop.

# DESIGN STEPS:
## Step 1:
HTML content creation.

## Step 2:
Design of webserver workflow.

## Step 3:
Implementation using Python code.

## Step 4:
Serving the HTML pages.

## Step 5:
Testing the webserver.

# PROGRAM:
```
<!doctype html>
<html>
<head>
<title> My Web Server</title>
</head>
<body align="center" bgcolor="pink">
    <h1>MY LAPTOP CONFIGURATION</h1>
    <table border="5" cellbadding="100" width="50%" align="center">
        <tr>
            <th>Configuration</th>
            <th>Description</th>
        </tr>
        <tr>
            <td>Processor</td>
            <td>13th Gen Intel(R) Core(TM) i5-13450HX        2.40 GHz 
            </td>
        </tr>
        <tr>
            <td>Primary Memory</td>
            <td>16 GB RAM</td>
        </tr>
        <tr>
            <td>system type</td>
            <td>64-bit operating system, x64-based processor</td>
        </tr>
        <tr>
            <td>Dedicated Graphic Memory Capacity
            </td>
            <td>4 GB</td>
        </tr>
        <tr>
            <td>SSD Capacity
            </td>
            <td>512 GB</td>
        </tr>
        <tr>
            <td>Primary Memory</td>
            <td>16 GB RAM</td>
        </tr>
        <tr>
            <td>Clock Speed
            </td>
            <td>Upto 4.4 GHz</td>
        </tr>
        <tr>
            <td>Screen Type</td>
            <td>Full HD, IPS, 300nits, Anti-glare, 100% sRGB, 144Hz Refresh Rate, G-SYNC
            </td>
        </tr>
    </table>
</body>
</html>
"""

class MyServer(BaseHTTPRequestHandler):
    def do_GET(self):
        print("Get request received...")
        self.send_response(200) 
        self.send_header("content-type", "text/html")       
        self.end_headers()
        self.wfile.write(content.encode())

print("Your web server is running....") 
server_address =('',8000)
httpd = HTTPServer(server_address,MyServer)
httpd.serve_forever()
```


# OUTPUT:

![Screenshot 2024-12-21 151629](https://github.com/user-attachments/assets/9fdfb470-f92d-4c4f-b317-83c5f8a46049)

![Screenshot 2024-12-21 151704](https://github.com/user-attachments/assets/5dd115b2-5380-4680-9d47-1ce422a481ff)




# RESULT:
The program for implementing simple webserver is executed successfully.
