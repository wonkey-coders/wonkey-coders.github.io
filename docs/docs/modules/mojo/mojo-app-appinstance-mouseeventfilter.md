_[mojo](../../modules/mojo/mojo-module.md):[mojo.app](../../modules/mojo/mojo-app.md).[AppInstance](../../modules/mojo/mojo-app-appinstance.md).MouseEventFilter_
##### Field MouseEventFilter:Void([MouseEvent](../../modules/mojo/mojo-app-mouseevent.md))
MouseEvent filter.

To prevent the event from being sent to a view, a filter can eat the event using [Event.Eat](mojo-app-appinstance-event.eat.md).

Filter functions should check if the event has already been 'eaten' by checking the event's [Event.Eaten](mojo-app-appinstance-event.eaten.md) property before processing the event.
