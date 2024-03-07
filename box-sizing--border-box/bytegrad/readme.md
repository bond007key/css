# box-sizing: border-box;
> Here "border-box" include the padding within the given "hight & width" --> so, actual box size doesn't increase.
>>[ ( "hight & width"+"padding" ) == total hight & width given] <-- that's why here box-size doesn't increases
# box-sizing: content-box; (Default value)
> Here "border-box" include the padding outside the given "hight & width" --> so, actual box size increases. 
>>[ ( "hight & width"+"padding" ) > total hight & width given] <-- that's why here box-size increases
