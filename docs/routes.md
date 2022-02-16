# Routes

## How to know Screen Name
This also include function on pop and push
1. Open `lib/routes/route_observer.dart` file in the project.
2. Breakpoint at 
```flutter
void _sendScreenView(PageRoute<dynamic> route) {
   🔴 var screenName = route.settings.name;
    action.call(screenName);
    // do something with it, ie. send it to your analytics service collector
  }
```

## Routing
- Open `lib/routes/route.dart` file in project to show screen navigation.

- Open `lib/common/constants/route_list.dart` file in project to show list of screen name (route list).

