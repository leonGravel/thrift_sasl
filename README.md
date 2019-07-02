# thrift_sasl.py

Thrift SASL Python module that implements SASL transports for Thrift
(`TSaslClientTransport`).

On Linux, this requires `libsasl2-dev` to be installed. On OS X you may have to
install Cyrus SASL v2 from source.

### update 
 fix TypeError: can't concat str to bytes
 https://github.com/leonGravel/thrift_sasl/pull/1
