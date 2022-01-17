# A24-Group
React Native Test

1. A functional component is just a plain javascript function that accept props as an argument and returns a react element, whereas a class component requires one to extend from react

2. myFunctionCall(++foo) will increment foo before the execution and myFunctionCall(for++) will increment after there execution

3. Flexbox,  it is great for because it accomodate the component and views in different scree sizes or even defferent devices

4. It will work dynamically on different screens sizes.

5. Negative margins are legal, because they you more control on the layout.

6. Jest

7. Debugging is at times difficult for faily new comers.

8. You need to render the component and mock the props that you expect.

React Native

9,10,11,13

const { width, height } = Dimensions.get('window');
const [height,setHeight] = useState();
const [time,setTime] = useState(00:00);

height: Platform.OS === 'android' ? height : height x 2;
const setTimeFun = () => {
return  setInterval(() => setTime({ time: Date.now() }), 100);
}


  <View {{borderColor:'grey', borderWidth:2, height:`${height}`}}>
    <Text>{width}</Text>
   <TextInput 
      onChangeText={((text)) => setHeight((text))
      value={height}
      />
  
      <Text>
    {setTimeFun() }
    </Text>


  </View>

  
