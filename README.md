Application simulating RustOS functionality 
- list all devices in network specified by network mask running this service
- First thread to broadcast identifier of application(mocked identifier)
- Second thread is listening on specific UDP port, if broadcast message matches our identifier pattern, it adds connected device to "known-devices" list
- This will use same crates as RustOS will use ( organizing into smaller crates or modules is not yet done )
- It would allow "connecting" to P2P network run by every device with  RustOS or Rusty application running

Current features
 - P2P Discovery service
 - Broadcasting service 
