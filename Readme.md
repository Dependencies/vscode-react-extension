# VSCode React extension sample

Sample of a VsCode extension using React.

This uses the WebView API for VsCode to create a visual extension using plain React for the front end.

The React application is designed to be decoupled from VsCode, so it can be debugged and developed using a normal browser. You should also be able to use all the usual npm packages (React Router, Redux, etc) as you would normally.

![What it looks like](./example.png)

## How to use

### Debug in VsCode

- Open the project in VsCode
- `npm install`
- Navigate to `/react-app`
- `npm install`
- Press `f5`
- Open the command selector (`ctrl+shift+p`)
- Search for the extension (`VsCode React extension`) and press enter

### Debug React UI by itself

- Navigate to `/react-app`
- `npm run start:dev`

## TODOs

- Set a content security policy for scripts