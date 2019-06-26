# Hoe kan RFID beveiligd worden?

### Deelvraag:

* Hoe doen andere vergelijkbare retailers dit? \(Van de deelvraag: **Hoe kan een product helpen om het betalingsproces te verbeteren?** \)

{% embed url="https://blog.atlasrfidstore.com/uhf-rfid-security-measures" %}

\(Smiley, 2018\)

### **Access Code**

The access code on UHF Gen 2 tags must be written in order to be used. Once written, the access code is stored on the reserved [memory bank](http://blog.atlasrfidstore.com/types-of-memory-in-gen-2-uhf-rfid-tags) along with the kill code and prevents anyone from changing the ‘lock’ state without first sending the 32-bit code. 

### **Kill Code**

The kill code is used primarily for applications that require tags to change state \(or phase\) to indicate a specific event has occurred. Applications like [retail](http://blog.atlasrfidstore.com/rfid-in-retail-is-making-noise) benefit from the kill code because once an item is purchased the tag can be killed, making it permanently unreadable. If this method is used, a reader is generally set up at the register to send the kill code after checkout. Using this state change, retailers are able to know if an item was actually purchased versus stolen if it is returned.

