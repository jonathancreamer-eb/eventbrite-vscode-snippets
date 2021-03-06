# Eventbrite VSCode Snippets
This repository is a collection of snippets for Visual Studio Code.  

![](https://d.pr/i/tXtAlp+)

## Installing and updating
To install...

```
git clone git@github.com:jonathancreamer-eb/eventbrite-vscode-snippets.git ~/.vscode/extensions
```

To update...

```
cd ~/.vscode/extensions/eventbrite-vscode-snippets
git pull
```

Then reload VS Code!

## Snippets
They are located in the `/snippets` directory.

| Snippet | Renders                               |
| ------- | ------------------------------------- |
| `eb-redux-basic-reducer`   | Basic Redux Reducer|
| `eds-basic-component`      | Basic EDS Component|

## Full Expansions

### eb-redux-basic-reducer - Basic Redux Reducer

```javascript
function $1(state = {}, {type, payload}) {
    switch (type) {
        case 'ACTION':
            return {
                ...state,
            };
        default:
            return state;
    }
};

export default $1;
```

### eds-basic-component - Basic EDS Component

```javascript
import React, {PureComponent} from 'react';
import PropTypes from 'prop-types';

/**
 * Component description
 */
export default class $1 extends PureComponent {
    static propTypes = {};

    render() {

        return (
            
        );
    }
}
```

## Adding Snippets
To add a snippet, first create an issue to track it.

Then you can add it to the corresponding snippet fild in `/snippets`.
