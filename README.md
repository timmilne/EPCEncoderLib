# EPCEncoderLib
Build the EPCEncoder lib and framework, includes Converter.

Note: most of this project leverages this great tutorial to create a framework:

http://www.raywenderlich.com/65964/create-a-framework-for-ios

I got the framework and the static library to work.  I opted to use the framework version because it packed all targets.
See the RFID apps: ValiTag, and RapiTag

libEPCEncoder.a was an intermediate step of the above tutorial, so I just dumped them all into the build
directory.  The completed framework is there as well.  Note, you need to build the Framework target in XCode
to get all this.  If you just build EPCEncoder, you won't get the framework or the lib in the build directory.
