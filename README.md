A simple currency converter. For the purpose of this demo, it uses data from https://exchangeratesapi.io/ but it is currently outdated (from 2021) because
in order to have the current databae, you have to sign up for a key.

If you get your hands on a private key and you'd like to use it for this demo, you have to:

1. add it as a value to `API_ACCESS_KEY` variable in the `src/App.js file`
2. in `src/components/DataContorller.js`:

  * remove `mockData` variable,
  
3.  in `componentDidMount` method:

  * remove `this.setState({ data: mockData })`;
  * uncomment `this.loadData()` line
    
---- Basic commands ---- 

1. npm install
2. npm start
