<h1 align="center">Virtual Customs App</h1>

<p align="center">
<img width=300" alt="Icon.png" src="/assets/Icon.png"><br />
</p>

[Electron][Electron] menubar application that wraps Virtual Customs.

---

**Requirements**

- [NodeJS][NodeJS]

---

**Instructions:**

- Run the following commands in your terminal:

```sh
npm i -g yarn && npm i git
git clone https://github.com/tbr-development/Virtual-Customs-App && cd Virtual-Customs-App
yarn install
yarn package
```

- Check the `out` folder for the packaged application to run.

---

**Notes**

- If you want to package a squirrel based app/installer, you can use `yarn make`. Once done check the `out/make` folder for your new squirrel based app/installer.
- Windows and linux users can use `Control+X` or `Command+X` to quit the app.
MacOS users can use `CMD+Q` to quit the app.
- It is recommended to have a systemwide ad blocker when using this app to get rid of excess ads. AdGuard Desktop has been tested to work perfectly with electron webapps.


[Electron]: https://www.electronjs.org/
[NodeJS]: https://nodejs.org
