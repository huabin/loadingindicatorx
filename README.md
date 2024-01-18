# LoadingIndicatorX
A Loading Indicator for React


### Demo

https://github.com/huabin/loadingindicatorx/assets/535675/f7ebbb69-433c-4439-ad08-4279bbdf86a4

You can also check the demo folder.

### Usage

Install it via

```
npm i loadingindicatorx
```

Use it in your project

1. import

```
import LoadingIndicator from 'loadingindicatorx';
```

2. Use

```
<LoadingIndicator loading={true} />
```

### Customize

```
<LoadingIndicator loading={true} spinnerProps={{ height: 100, width: 100, borderThickness: '5px', borderTopThickness: '2px', borderColor: '#FF5722', animationDuration: 2 }} />
```

height - The spinner's height

width - The spinner's width

borderThickness - The thickness of the spinner's border

borderTopThickness - The thickness of the spinner's borderTop

borderColor - The color of the spinner's border

animationDuration - Animation Duration

### License

Based on [MIT](LICENSE)

