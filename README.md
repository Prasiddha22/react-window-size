# @prasiddha/react-window-size

@prasiddha/react-window-size provides with a useWindowSize hook.

## Installation

Use the package manager [npm](https://nodejs.org/en/) to install react-simple-spoiler.

```terminal
npm install @prasiddha/react-window-size --save
```

## Usage

```tsx
import { useWindowSize } from '@prasiddha/react-window-size';

const App = () => {
  const { width, height } = useWindowSize();
  return (
    <div
      style={{
        height: '100vh',
        width: '100vw',
        display: 'flex',
        justifyContent: 'center',
        alignItems: 'center',
      }}
    >
      <div>
        <h1>Height:{height}</h1>
        <h1>Width:{width}</h1>
      </div>
    </div>
  );
};

export default App;

export default App;
```

## Props

--

###

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
