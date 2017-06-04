# React Native Event Calendar
A React Native iOS style calendar implemented using VirtualizedList.

This is a WIP project and the API is currently being fleshed out. 

## Demo
<a href="https://raw.githubusercontent.com/joshyhargreaves/react-native-event-calendar/master/demo/demo.mp4"><img src="https://raw.githubusercontent.com/joshyhargreaves/react-native-event-calendar/master/demo/demo.gif" width="360"></a>

## Current API
Proper documentation coming soon...

`EventCalendar` can be configured through a `style` prop whereby any of the components in the calendar can be styled. 
```
    {
        container: {
            backgroundColor: 'white'
        }, 
        event: {
            opacity: 0.5
        }
    }
```

## Proposed API changes
Coming soon...

## TODO
- Accept dates as props for start and end times of events
- Add optional max, end date props
- Add starting date prop
- Add onDateChanged cb prop Accept dates as props
- General API review/clean-up. 

## Examples
See Examples dir. 
N.B. the example project won't start in the middle of the VirtualizedList as 
`initialScrollIndex` not in Expo SDK as of yet. 
But this will work in a more up to date version of React-native. 
