# Pet Battle Analytics

## Based on Fathom https://github.com/usefathom/fathom 

Fathom and Fathom logo are trademarks of Fathom Analytics.

## Usage
The analytics service is an ephemeral service with no long term storage. 

It uses a sqllite database in running in the pod.

On installation via helm there are two config maps created by defautt

* fathom-client-js - contains the client javascript snippet to be embedded into the Client User Interface
* fathom-client-config - contains the hostname and tracking ID to be used by the fathom-client-js script




