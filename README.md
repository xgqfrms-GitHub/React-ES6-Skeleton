# React-ES6-Skeleton

## React ES6 Skeleton

https://gist.github.com/xgqfrms-GitHub/0a02e84d25cfeeb60d3c71e2a8ff1e91


```jsx
import React,{Component} from 'react';
import ReactDOM from 'react-dom';
import HelloWorld from 'react-npm-skeleton';

class XyzComponent extends Component {
    constructor(props){
        super(props);
        this.methods = this.methods.bind(this);
    }
    render() {
        return(
            <div>
                <HelloWorld />
                <input
                    type="text"
                    ref={(input) => { this.textInput = input; }}
                />
                <input
                    type="button"
                    value="Focus the text input"
                    onClick={this.focus}
                />
            </div>
        );
    }
}

export default XyzComponent;

ReactDOM.render(<App />,document.querySelector('#app'));



``` 






