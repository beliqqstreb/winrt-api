---
-api-id: P:Windows.ApplicationModel.Activation.ContactCallActivatedEventArgs.ServiceUserId
-api-type: winrt property
---

<!-- Property syntax
public string ServiceUserId { get; }
-->

# Windows.ApplicationModel.Activation.ContactCallActivatedEventArgs.ServiceUserId

## -description
Gets the user identifier of the service used for the call.

## -property-value
The user identifier of the service used for the call.

## -remarks
For PSTN calls, the ServiceUserId property is set to the PSTN number for the contact. For web-based services, the ServiceUserId property is set to the contact’s user id for that particular service.

For info about how to handle app activation through contact actions, see [Quickstart: Handling contact actions ](https://docs.microsoft.com/previous-versions/windows/apps/dn518236(v=win.10)) and [Quickstart: Handling contact actions ](https://docs.microsoft.com/previous-versions/windows/apps/dn518338(v=win.10)).

## -examples

## -see-also
[Handling Contact Actions sample](https://go.microsoft.com/fwlink/p/?LinkID=320151)
