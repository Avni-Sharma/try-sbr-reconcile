The reconciler shows logs of watches on the backend CRD

```
2020-08-25T07:50:03.192+0530	DEBUG	watch.CSVToWatcherMapper	Adding watch for GVK	{"Obj.NamespacedName": "default/backend-operator.v0.1.0", "GVK": "stable.example.com/v1, Kind=Backend"}
2020-08-25T07:50:03.192+0530	DEBUG	sbrcontroller	Adding watch for GVK...	{"GVK": "stable.example.com/v1, Kind=Backend"}
2020-08-25T07:50:03.192+0530	DEBUG	sbrcontroller	Skipping watch on GVK twice, it's already under watch!	{"GVK": "stable.example.com/v1, Kind=Backend"}
2020-08-25T07:50:03.299+0530	DEBUG	olm	Reading CSV to extract GVKs...	{"CSV.NamespacedName": "default/backend-operator.v0.1.0"}
2020-08-25T07:50:03.605+0530	DEBUG	olm	Inspecting CRDDescription...	{"CRDDescription": {"name":"backends.stable.example.com","version":"v1","kind":"Backend","description":"Backend is the Schema for the backend API"}}
2020-08-25T07:50:03.605+0530	DEBUG	olm	Extracting GVK from CRDDescription	{"CRDDescription.Name": "backends.stable.example.com"}
2020-08-25T07:50:03.605+0530	DEBUG	watch.CSVToWatcherMapper	Adding watch for GVK	{"Obj.NamespacedName": "default/backend-operator.v0.1.0", "GVK": "stable.example.com/v1, Kind=Backend"}
```
