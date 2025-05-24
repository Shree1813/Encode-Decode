# Encode-Decode
This code could change Decode to Encode and Encode to Decode Offline.
#Encode a Stirng to Base64
import base64

text = "rtsp://rtsp:rtsp@............." ##change the text value according to your Encode
encode_text = base64.b64encode(text.encode('utf-8'))
print(encode_text.decode('utf-8'))


#Decode a Base64 String

encode_text = "cnRz..................."   ##change the text value according to your Decode
decode_text = base64.b64decode(encode_text).decode('utf-8')
print(decode_text)
