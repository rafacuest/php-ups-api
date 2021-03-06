# CHANGELOG

## 0.6.0 (released 25-09-2015)
- Extra check on response in QuantumView, when no response it gave an error
- Added ShipmentRequestLabelSpecification class for easier options setting
- Added ShipmentRequestReceiptSpecification class for easier options setting
- **[!]** Shipment class dropped some public properties in favor of private properties and setter/getter methods.
- **[!]** `confirm` and `accept` methods of Shipping class now receive Shipment, ShipmentRequestLabelSpecification and
ShipmentRequestReceiptSpecification

Items marked with **[!]**  may and will incur backwards incompatibility.

## 0.5.2 (released 16-09-2015)

- TimeInTransit ServiceSummary results should be array of summaries, which was not the case when 1 result

## 0.5.1 (released 08-09-2015)

- Limit alternate delivery address names to 35 characters

## 0.5.0 (released 26-08-2015)

- Added UTF8 compatibility for UPS responses
- Added Guzzle to handle requests
- Changed required PHP version to 5.5
- Removed Autoloader in favor of composer
