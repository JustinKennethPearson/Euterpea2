
This is my own fork of Euterpea so that it is actually usable. Donya
Quick does not seem to have time to update the repository and
currently it is impossible to use because of the outdated cabal
file. I am not a cabal expert, but I have modernised the cabal file a
bit and taken out all the version numbers so that it picks up the
latest versions  of the packages. As of now it seems to run with ghc
version 9.0.1. There is a lot that should be done: for example taking
out support for ghc < 6 , which would eliminate the need for using the
CPP extension; and modernising some of the code.



Version 2.0.8
Last modified: 16-June-2019
Website: http://www.euterpea.com
 _____      _                             
|  ___|    | |                            
| |__ _   _| |_ ___ _ __ _ __   ___  __ _ 
|  __| | | | __/ _ \ '__| '_ \ / _ \/ _` |
| |__| |_| | ||  __/ |  | |_) |  __/ (_| |
\____/\__,_|\__\___|_|  | .__/ \___|\__,_|
                        | |               
                        |_|               


Maintainers:
  Donya Quick <donyaquick@gmail.com>

Authors:
  Paul Hudak
  Eric Cheng
  Hai (Paul) Liu
  Donya Quick 
  Dan Winograd-Cort 

Euterpea is a domain-specific language embedded in Haskell for 
computer music research, education, and development, providing 
both note-level and signal-level abstractions.  It is a descendant 
of Haskore and HasSound, and is intended for both educational purposes 
as well as serious computer music applications.  Euterpea is a 
wide-spectrum DSL, suitable for high-level music representation, 
algorithmic composition, and analysis; mid-level concepts such as 
MIDI; and low-level audio processing, sound synthesis, and instrument 
design.  

See the License file for licensing information.

If you are experiencing a problem with Euterpea, please first check the 
GitHub version of the library: https://github.com/Euterpea/Euterpea2
Bugs still found in the GitHub version should be reported using the 
issues page: https://github.com/Euterpea/Euterpea2/issues

PULL REQUESTS WILL BE IGNORED. Bug fixes should be submitted through
the issues page with a detailed explanation of the alterations.

Please send any other questions and comments to Donya Quick 
(donyaquick@gmail.com).

Installation instructions and additional examples are available at
the Euterpea website: http://www.euterpea.com
