# REACT NOTE APP

A note app made with `react` with a custom rich text editor made with `firebase`.

## Firebase🔥

Google Firebase is a Google-backed application development software that enables developers to develop iOS, Android and Web apps.Here our app **afternotes** which is a web app, depends on firebase for the following features.

- **Firebase Auth 🦸**
  Every app requires an authentication system,firebase provides us with basic `email and password` signin and along with all the major OAuth providers like `facebook`,`google` and many others .
  For this project we are mainly using above cited providers only.

- **Cloud firestore 🧮**
  Cloud firestore is the database of our project .The cloud firestore is a `NoSql` database similar to `monogdb`.The data is being stored in the cloud firestore approximately like the `graph `shown below.
- **Cloud Storage🏪**
  As we have authenticated the user ,we need to make a profile page which ➡️ leads to the use cloud storage.`cloud storage` is simply a storage bucket to store the files.
  ```mermaid
  stateDiagram
  user --> picture1
  user --> picture2
  credentials --> picture2
  ```
  The last saved or added image is used as the user image
- **Hosting🌏**
  Being a web project, thus taking advantage of firebase hosting and following the [instruction](https://firebase.google.com/docs/hosting/quickstart).The project can be easity hosted.[URL](https://notify-b3141.web.app/)
> 👽 Project is not finished

## Conclusion ✋

The project is done properly ,but not good for usage.
