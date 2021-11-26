Steps to rebuild the project:

```
git clone https://github.com/sohamp19/react-task-tracker
```

Make sure you are in the project directory

```
cd react-task-tracker
```

Install the modules and build the project:

```
npm install
npm run build
```

Connect to the mock backend:

```
npx json-server --watch db.json --port 3333
```

View the project:

```
npx serve -s build
```

