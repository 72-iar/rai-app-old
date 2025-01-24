Before proceeding please download and install the following dependencies:

Node.js: https://nodejs.org/en

Composer: https://getcomposer.org

--------------------------------------------------------------------------------------------------------------------------------------------------

Instructions:

Download and extract the zip to your desired path.

Open your VS Code.

In your VS Code click "File" on the top left click "Open Folder" then look for the extracted zip.

After that, you should be seeing something like this:
![screenshot](https://github.com/72-iar/rai-app/blob/9f46cd453fedf963eae7c609a55a16408e962235/readme-pic-1.png)


Rename ".env.example" to ".env".

Open a terminal on the vs code and do the following:
- npm install
- (wait for it to finish)
- npm run dev

Open another terminal (dont close the previous one) and do the following:
- composer install
- (wait for it to finish)
- php artisan serve


Click the link provided on the terminal.
(most likely: http://127.0.0.1:8000)

You'll be redirected to your default browser:
![screenshot](https://github.com/72-iar/rai-app/blob/783846c4ab6234ed0530f99823814db047d3e583/preview.png)
