# react-native-view-loading-ethan

<img src="./img/IMG_0380.GIF" width="200" alt="react-native-view-loading-ethan" />

## 安装

```
npm install react-native-view-loading-ethan --save
```

## 使用

```

import ViewLoadingEthan from 'react-native-view-loading-ethan';

const App = () => {
    return (
        <ViewLoadingEthan 
            lineWidth={2}
            size={50}
            lineColor={'#000'}
        />
    )
}
export default App;

```
## props

```
PropTypes = {
    lineWidth:PropTypes.number,
    size:PropTypes.number,
    lineColor:PropTypes.string
}
```

## defaultProps
```
defaultProps = {
    lineWidth:2,
    size:50,
    lineColor:'#000'
}
```
