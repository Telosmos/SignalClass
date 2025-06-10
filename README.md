# SignalClass
A class that reimplements the functionality of BindableEvents (for features like a custom PlayerAdded). One use-case is to pass tables through without them losing their metatable. Another use-case is being able to pass cyclic tables through the signal without erroring. The point of this class is to reimplement BindableEvent but remove the restrictions.
