# TLVQR
TLV QR code decrypted for ZACAT in Kingdom of Saudi Arabia


how to use :
- add this class to your project
- rename namespace to your namespace
- download missing package
- create object from class like this ;
 TLVCls tlv = new TLVCls("Company Name", "VAT Number", DateTime.Now, 100, 15);
            pictureBox1.Image = tlv.toQrCode();
where 100 is : total invoice
      15  is : vat value
