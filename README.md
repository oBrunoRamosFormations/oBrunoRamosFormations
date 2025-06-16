## Hi there 👋

~~~shell
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
~~~

~~~shell
choco install nodejs -y
~~~
~~~shell
npm install -g typescript && tsc --init
~~~
~~~json
"scripts": {
  "start:dev": "ts-node src/arquivo.ts"
}
~~~
~~~shell
npm run start:dev
~~~
