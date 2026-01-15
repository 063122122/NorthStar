# PathMem - Personal Route Intelligence System

A Progressive Web App that learns your walking routes and helps you navigate using your personal shortcuts.

## Features

- **Route Recording**: GPS tracking of your walks with distance, duration, and breadcrumb points
- **Place Saving**: Save frequently visited locations (Home, Work, Gym, etc.)
- **Compass Navigation**: Visual compass pointing to your destination
- **Route Mesh Learning**: Automatically identifies where your routes intersect for smarter navigation
- **Offline Support**: Works without internet once installed
- **No Account Required**: All data stored locally on your device

## How to Use

### Recording a Route
1. Open the app and go to the "Record" tab
2. Wait for GPS signal (shows accuracy)
3. Tap the big button to start recording
4. Walk your route
5. Tap again to stop
6. Enter a name and save

### Saving a Place
1. Go to the "Places" tab
2. Make sure you're at the location you want to save
3. Tap "+ Add Current"
4. Enter a name (e.g., "Home", "Work", "Livi Centre")

### Navigating
1. Go to the "Navigate" tab
2. Select a destination from the dropdown
3. The compass will point toward your destination
4. Distance and ETA shown below

## Technical Notes

- **GPS Accuracy**: Works best outdoors with clear sky view
- **Battery Usage**: GPS polling is optimized but will use some battery when recording
- **Data Storage**: All data stored in IndexedDB (browser local storage)
- **Privacy**: No data leaves your device - everything is local

## Route Mesh Intelligence

The app builds a "mesh" of your routes over time:
- It identifies where different routes cross each other
- Uses this to suggest optimal paths combining multiple routes
- The more you walk, the smarter it gets

## Future Ideas

- [ ] Route sharing with friends
- [ ] Cloud backup (optional)
- [ ] Estimated arrival notifications
- [ ] Integration with fitness trackers
- [ ] Voice guidance option
- [ ] Dark/light theme toggle

## Troubleshooting

**GPS not working?**
- Make sure location permission is granted
- Try going outside - GPS works poorly indoors
- Check if battery saver mode is blocking GPS

**App not installing?**
- Must access via HTTPS (GitHub Pages provides this)
- Try clearing browser cache
- Make sure you're using Chrome (Android) or Safari (iOS)

**Routes not saving?**
- Check browser storage isn't full
- Try recording a longer route (minimum 5 GPS points needed)

## License

ArcadiaProducts

Built for Walkers!

