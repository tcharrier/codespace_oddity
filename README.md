# codespace_oddity

Let's go


## Build Setup - Option 1

### Install MongoDB
Detailed instructions can be found on https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/ but here's the run down for macOS: 
- Install XCode 
- Install Homebrew (see https://brew.sh/#install for instructions)
- Tap the MongoDB Homebrew Tap
```bash
$ brew tap mongodb/brew
```
- Install MongoDB
```bash
$ brew install mongodb-community@4.4
```

### Install npm & node
Go to https://www.npmjs.com/get-npm, download and install the right installer for your platform. We are currently using version `14.10.1`.


### Clone the repo

```bash
$ git clone https://github.com/octodemo/codespace_oddity.git
$ cd codespace_oddity
```
### Install dependancies 

```bash
$ npm install
```

### Serve with hot reload at localhost:3000
$ npm run dev

## Build Setup - Option 2
- Create a new Codespace
- Click the run button
- Start coding now!!

## build for production and launch server
```bash
$ npm run build
$ npm run start
```
