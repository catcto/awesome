This is an archived snapshot of [awesome-pascal](https://github.com/Fr0sT-Brutal/awesome-pascal) just before it turned from "Delphi" to "Pascal".
=================================================================================================================================================
It was left only to keep links alive. All development will happen in [awesome-pascal](https://github.com/Fr0sT-Brutal/awesome-pascal) list.
===========================================================================================================================================

## Awesome Delphi [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Delphi frameworks, libraries, resources, and shiny things. Inspired by awesome-... stuff.

**Note that only open-source projects are considered. Dead projects (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/not updated for 3 years or more) are mainly ignored except for those which do not have alive analogs.**
Feel free to suggest other missing nice projects either by comments or pull requests.

This awesome collection is also available on [Delphi.ZEEF.com](https://delphi.zeef.com/anton.frost)

## Contents ##

- [Awesome Delphi](#awesome-delphi)
	- [General Libraries](#general-libraries)
	- [Multimedia](#multimedia)
		- [Audio](#audio)
		- [Video](#video)
		- [Graphic](#graphic)
	- [Game dev](#game-dev)
	- [Communications](#communications)
		- [Network](#network)
		- [Serial port](#serial-port)
	- [GUI](#gui)
		- [Control packs](#control-packs)
		- [Single controls](#single-controls)
		- [Editors](#editors)
		- [Viewers](#viewers)
		- [Other GUI](#other-gui)
	- [Database](#database)
	- [Scripting](#scripting)
	- [Non-visual Classes/Utils](#non-visual-classesutils)
		- [Compression](#compression)
		- [Encryption](#encryption)
		- [XML/JSON/YAML](#xmljsonyaml)
		- [Language](#language)
		- [Memory managers](#memory-managers)
		- [System](#system)
		- [Template](#template)
		- [Logging](#logging)
		- [Math](#math)
		- [Other non-visual](#other-non-visual)
	- [OS](#os)
	- [Report generating](#report-generating)
	- [Unit Testing](#unit-testing)
	- [Debugging / error handling](#debugging--error-handling)
	- [Utilities](#utilities)
		- [IDE plugins/wizards](#ide-pluginswizards)
		- [Documentation](#documentation)
		- [Code check/review, debug](#code-checkreview-debug)
		- [Setup](#setup)
		- [Other](#other)

----------------------------------------------------------------------------------------------------------------

## General Libraries ##
*Big general-purpose libraries*

* [JCL](https://github.com/project-jedi/jcl). Set of thoroughly tested and fully documented utility functions and non-visual classes which can be instantly reused in your Delphi and C++ Builder projects. The library is grouped into several categories such as Strings, Files and I/O, Security, Math and many, many more.

* [JVCL](https://github.com/project-jedi/jvcl). Library of over 600 Delphi components developed by "Project JEDI" members.
// *GUI, algorithms, classes, API headers etc.*

* [Alcinoe](http://sourceforge.net/projects/alcinoe). Components suite for Delphi.
// *Network: FTP/Http/NNTP/POP3/SMTP, ISAPI, WinInet Http/FTP clients; DB: Firebird/MySQL/SQLite3/Memcached/MongoDb/SphinxQL; XML/JSON Parser; ZLIB; Cryptography: AES, Blowfish, MD5, SHA, secure keyed MD5/SHA; Other: Self-Balancing Binary Trees, expression evaluator*

* [Fundamentals Code Library](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://sourceforge.net/projects/fundementals) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/abandoned, more recent fork is [here](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/fundamentalslib/fundamentals4) - though it slightly differs in units set, f.ex. no XML. Recent major version 5 [here](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/fundamentalslib/fundamentals5)). Collection of Delphi / FreePascal code units. Includes libraries for Unicode, Strings, Data Structures, Sockets and Mathematics.
// *Utils: ZLIB compression; JSON; XML; ProtocolBuffers; Unicode routines; data structures; Hashes: XOR, CRC, Adler, MD5, SHA, secure keyed MD5/SHA, etc; Network: blocking TCP client/server, HTTP(https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/S) via SSL3/TLS1.0/TLS1.1/TLS1.2 (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/fully native); SQL parser; BitCoin MtGox client; Blaise script engine; Cipher: AES, DES, FUNE, RC2, RC4, RSA, Diffie-Hellman; Maths: matrix, complex, statistics, huge numbers*

* [Spring4D](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://bitbucket.org/sglienke/spring4d). Open-source code library for Embarcadero Delphi 2010 and higher. It consists of a number of different modules that contain a base class library (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/common types, interface based collection types, reflection extensions) and a dependency injection framework. Includes Encryption Library.
// *Collections and other containers using Generics and based on IEnumerable, probably more accurate and featured than RTL analogs; crypto: CRC, DES, MD5, SHA; file utils etc*

* [TheUnknownOnes](https://github.com/chaosben/theunknownones). Huge heap of classes, components, utilities for almost every purpose. Nearly undocumented and seems not very up-to-date though.

* [CNVCL](https://github.com/cnpack/cnvcl). CnPack Component Package. Large collection of visual components, classes and utilities. // *Lots of useful stuff; documentation and comments mainly in Chinese*

* [mORMot](https://github.com/synopse/mORMot). Client-Server ORM/ODM SOA MVC framework for Delphi 6 and higher, or FPC 2.7. Direct SQL/NoSQL database access, ORM/ODM over objects, RESTful ORM and SOA services via interfaces over high performance HTTP server, MVC/MVVM web sites, testing including mocks and stubs, logging, cryptography, compression, huge documentation.

* [MARS - Curiosity](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/andrea-magni/MARS). Delphi REST Library. Pure REST approach, standard concepts in a familiar Delphi flavor (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/including a component based client library). Known compatibility: Delphi versions from XE to 10 Seattle. Some functionalities requires FireDAC.

* [ADAPT](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/LaKraven/ADAPT). Advanced Developer Async Programming Toolkit, foundation library intended to be used at the heart of your projects for the purpose of providing extremely powerful, multi-threaded (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/and thread-safe) capabilities. Event Engine - a very powerful system for producing Multi-Threaded, Asynchronous and Event-Driven programs. Generics Collections - highly efficient Collection Types (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Lists, Trees, Maps etc.). Math Library - a library for Unit Conversion, special calculation and other useful mathematics routines. Package Engine - extension of the Streamables Engine supporting the packaging of files together (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/a VFS of sorts). Shared Streams Library - 100% Thread-Safe Stream Classes (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Interfaced too) allowing read/write from multiple Threads. Stream Handling Library - makes working with Streams much easier! Handles Deleting, Inserting, Reading and Writing data.

* [Redux Delphi](https://github.com/pierrejean-coudert/ReduxDelphi). Predictable state container for Delphi apps utilizing a unidirectional data flow. Inspired by ReduxJS. Comes with Immutable Generic List.

* [GrijjyFoundation](https://github.com/grijjy/GrijjyFoundation). Foundation classes and utilities that are used throughout the other Grijjy Repositories.
// *BSON/JSON, IOCP/EPOLL sockets, socket pools, HTTP, HTTP/2, OpenSSL, ProtocolBuffers.*

* [unRxLib](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://www.micrel.cz/RxLib/dfiles.htm). Effort to keep RxLibrary (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/library of 60+ components) actual.

* [QuickLib] (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/exilon/QuickLib). Delphi/freepascal (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Windows/Linux) library for Quick development and crossplatform support (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Json Serialize, AutoMapper, Chronometer, Threads, Lists, Config, Console services and more).


## Multimedia ##


## Audio

* [Audio Tools Library](http://mac.sourceforge.net/atl). For manipulating many audio formats file information.
//**Abandoned since 2005.**

* [Delphi ASIO & VST Project](http://sourceforge.net/projects/delphiasiovst). Framework for writing applications using the ASIO interface and VST plugins. It comes with countless DSP algorithms all demonstrated in dozens of examples.
//*Not very active lately, but the trunk is in a usable state .*

* [NewAC - New Audio Components](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://code.google.com/p/newac) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/abandoned, list of forks on GH [here](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/search?l=Pascal&o=desc&q=newac&s=updated&type=Repositories)). Designed to help your Delphi programs perform different sound processing tasks. With NewAC you can play audio stored in many formats (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/wav, Ogg Vorbis, FLAC, Monkey Audio, WavPack, MP3, Windows WMA, DTS, AC-3 (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Dobly Surround), VOB (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/DVD files)).
// *Playback, recording, tag read/write, some audio editing tasks and conversions*

* [Audorra](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://sourceforge.net/projects/audorra). Digital audio library for Delphi and Freepascal. Using a flexible plugin architecture, it allows you to exchange the audio backend (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/e.g. WaveOut, OpenAL), add protocol classes (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/e.g. file, http) and decoders.


## Video

* [DSPack](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://code.google.com/p/dspack) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/abandoned, active fork is [here](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/micha137/dspack-continued-mirror-for-delphinus)). Set of components and classes to write Multimedia Applications using MS Direct Show and DirectX technologies.

* [Delphi-OpenCV](https://github.com/Laex/Delphi-OpenCV). Translation of OpenCV library header files in Delphi
// *Includes FFMPEG headers*

* [FFmpeg Delphi/Pascal Headers](http://www.delphiffmpeg.com/headers). Open source translation of FFMPEG headers.

* [PasLibVlc](http://prog.olsztyn.pl/paslibvlc). Interface to VideoLAN libvlc.dll and VCL player component for Delphi / FreePascal based on VideoLAN


## Graphic

* [Graphics32](https://github.com/graphics32/graphics32). Designed for fast 32-bit graphics handling on Delphi, Kylix and Lazarus. Optimized for 32-bit pixel formats, it provides fast operations with pixels and graphic primitives, and in most cases Graphics32 outperforms the standard TCanvas classes. It is almost a hundred times faster in per-pixel access and about 2-5 times faster in drawing lines.

* [GraphicEx](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://www.delphi-gems.com/index.php/libs/graphicex-library). Addendum to Delphi's Graphics.pas to enable your application to load many common image formats. This library is primarily designed to load images as background (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/buttons, forms, toolbars) and textures (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/DirectX, OpenGL) or for image browsing and editing purposes as long as you don't need to save images.

* [Vampyre Imaging Library](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://imaginglib.sourceforge.net). Cross-platform native Object Pascal (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Delphi and Free Pascal) image loading, saving, and manipulation library.

* [CCR-EXIF](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://code.google.com/p/ccr-exif) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/seems abandoned, list of forks on GH [here](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/search?l=Pascal&o=desc&q=ccr-exif&s=updated&type=Repositories)). Library to read and write Exif, IPTC and XMP metadata from JPEG, TIFF and PSD images.

* [KIcon](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://www.tkweb.eu/en/delphicomp/kicon.html). This component makes sense if a more complex manipulation with icons (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/or better icon files *.ico) than just viewing is needed. Full PNG icon image support, correct rendering, icons with alpha channel.

* [Delphi Twain](http://www.kluug.net/delphitwain.php). The library allows you to easily access scanning functions from Delphi and Lazarus.

* [Synopse PDF](https://github.com/synopse/SynPDF). Fully featured Open Source PDF document creation library for Delphi, embedded in one unit. Pure Delphi code, Delphi 5 up to XE7, for Win32 and Win64 platforms.

* [PowerPDF](https://github.com/TurboPack/PowerPDF). VCL component to create PDF docment visually. Like Forms, you can design PDF document easily on Delphi or C++Builder IDE.

* [IGDI+](https://sourceforge.net/projects/igdiplus). The free open source library allows quick and easy implementations of complex GDI+ applications, in a natural Delphi-friendly code.

* [GLScene](https://sourceforge.net/projects/glscene). OpenGL based 3D library for Delphi. It provides visual components and objects allowing description and rendering of 3D scenes in an easy, no-hassle, yet powerful manner. GLScene is not just an OpenGL wrapper or utility library, it has grown to become a set of founding classes for a generic 3D engine with Rapid Application Development in mind. GLScene allows you to quickly design and render 3D scenes without having to learn the intricacies of OpenGL, if you know how to design a TForm, you'll easily master the basic operations of GLScene. The library comes with a large collections of demos showcasing the ease of use, and demonstrating RAD wasn't done at the expense of CPU/GPU horsepower.

* [SynGdiPlus](https://github.com/synopse/mORMot/blob/master/SynGdiPlus.pas). Enables an application to load and save GIF, TIF, PNG and JPG pictures. It also allows anti-aliased drawing from any TMetaFile. That is, you can play a .emf content using GDI+ instead of GDI, for much better rendering result.

* [mORMotReport](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/synopse/mORMot/blob/master/SQLite3/mORMotReport.pas) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/[docs](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://synopse.info/files/html/api-1.18/mORMotReport.html)). Fast and efficient code-based reporting component, with preview form and PDF export.

* [Andorra 2D](http://sourceforge.net/projects/andorra). New generation 2D Engine for Delphi and Lazarus. Andorra 2D is capable to use DirectX or OpenGL through graphic plugins. Andorra 2D is built in a very modular way and is yet easy to use.

* [Transparent-canvas](https://github.com/vintagedave/transparent-canvas). Delphi VCL / Windows project for drawing semi-transparent alphablended graphics. It provides a class similar to TCanvas.

* [Fully-justified-text](https://github.com/vintagedave/fully-justified-text). Delphi VCL / Windows project for text output, allowing printing of fully justified text with a variety of options.

* [AsciiImage](https://github.com/Memnarch/AsciiImage). AsciiImage-Implementation for Delphi by Alexander Benikowski based on AsciiImage by Charles Parnot. Read more on [his article](http://cocoamine.net/blog/2015/03/20/replacing-photoshop-with-nsstring).
// *Creates scalable monochrome image from ASCII pixel map*

* [PngComponents](https://bitbucket.org/uweraabe/pngcomponents). PngComponents is a set of components that allows you to include in your application real PNG files. PNG files on their own do not generate an enourmous advantage, but their support for an alpha-channel does indeed have quite a charm to it.

* [AggPasMod](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/CWBudde/AggPasMod). Modernized Pascal Anti-Grain Geometry. Based on AggPas, which is itself based on the Anti-Grain Geometry, this project offers support for the latest Delphi Versions (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/XE and above) and contains some helper classes (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/VCL components and FireMonkey interface). 2D vector graphics library. Basically, you can think of AggPas as of a rendering engine that produces pixel images in memory from some vectorial data. But of course, AGG can do much more than that.
// *Vector graphic library, renders SVG and much more*

* [delphi-shader](https://github.com/WouterVanNifterick/delphi-shader). Hundreds of graphical effects, and a library that provides GLSL functionality in pure Delphi code. This project produces an executable with more than a hundred real-time graphical effects. All that is a 100% pascal implementation, without the use of exernal libraries or hardware acceleration.

* [dglOpenGL](https://github.com/SaschaWillems/dglOpenGL). Delphi / Pascal OpenGL header translation.

* [DelphiZXingQRCodeEx](https://github.com/MichaelDemidov/DelphiZXingQRCodeEx). Delphi port of the QR Code generating functionality from ZXing, an open source barcode image processing library.

* [ZXing.Delphi](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/Spelt/ZXing.Delphi). Native Object Pascal library for Delphi XE to 10.2 Tokyo that is based on the well known open source Barcode Scanning Library ZXing (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Zebra Crossing). It is aimed at all of the FireMonkey mobile platforms and, starting from v3.1, it fully supports also Windows VCL applications (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/no dependencies on FMX.Graphics unit).

* [QuickImageFX](https://github.com/exilon/QuickImageFX). Delphi library for simplifying image load/save, conversion and transformation. Load/save png, jpg, gif and bmp. get image from different resources: file, stream, http, imagelist, associated windows icon, executable file icon, etc... Rotate, flip, grayscale and many other transformations.

* [NativeJpg](https://code.google.com/p/simdesign). Fully object-oriented Pascal implementation that allows to read and write Jpeg files. You can use this software to read and write Jpeg images from files or streams. It supports baseline and progressive Jpeg, support for metadata, as well as all conceivable lossless operations.


## Game dev ##

* [RecastNavigation](https://github.com/Kromster80/RecastNavigationDelphi). Navigation mesh construction toolset for games. Recast is accompanied with Detour, path-finding and spatial reasoning toolkit. You can use any navigation mesh with Detour, but of course the data generated with Recast fits perfectly. This is a port of the original RecastNavigation written in C++.

* [Kraft Physics Engine](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/BeRo1985/kraft). Open source Object Pascal physics engine library that can be used in 3D games. Compatible with: Delphi 7-XE7 (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/but not with the Android and iOS targets), FreePascal >= 2.6.2 (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/with almost all FPC-supported targets including Android and iOS) 

* [ZenGL](https://github.com/andru-kun/zengl). OpenGL Cross-platform game development library written in Pascal, designed to provide necessary functionality for rendering 2D-graphics, handling input, sound output, etc. 
// *Not updated lately, but is working ok* 

* [Platform eXtended Library (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/PXL)](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://sourceforge.net/projects/asphyre). Cross-platform framework for developing 2D/3D video games, interactive and scientific applications. It aids the developer with mathematics, hardware control, resource management, displaying real-time graphics and text, handle user input and network communication capabilities.

* [CrystalPathFinding](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/d-mozulyov/CrystalPathFinding). Simple and effective library with an open source intended for the searching of the shortest paths by algorithms A*/WA* for maps based on tiles with 4 (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/simple), 8 (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/diagonal/diagonalex) or 6 (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/hexagonal) neighbors.

* [Allegro-Pas](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://sourceforge.net/projects/allegro-pas) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/[GitHub](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/niuniomartinez/allegro-pas)). Wrapper to use the Allegro game library with Pascal/Delphi.

* [Castle Engine](https://github.com/castle-engine/castle-engine). Complete Pascal Game Engine. Cross-platform 3D and 2D game engine with a lot of graphic effects and a scene graph based on X3D.

* [TileEngine](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://www.tilengine.org). (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/[GitHub](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/turric4n/PascalTileEngine)) OOP Pascal Wrapper and bindings for Tilengine 2D retro graphics engine. Tilengine is a cross-platform 2D graphics engine for creating classic/retro games with tilemaps, sprites and palettes. Its scanline-based rendering algorithm makes raster effects a core feature, a technique used by many games running on real 2D graphics chips.

* [SDL2](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://www.freepascal-meets-sdl.net/) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/[GitHub](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/ev1313/Pascal-SDL-2-Headers)). Pascal SDL 2 Headers. Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D.

* [SFML](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/CWBudde/PasSFML). Pascal SFML Headers. SFML provides a simple interface to the various components of your PC, to ease the development of games and multimedia applications. It is composed of five modules: system, window, graphics, audio and network. Currently Delphi and FPC/Lazarus are supported. However, due to a compiler incompatibility with the Delphi compiler (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/solved with workarounds), FPC is recommended at the moment.

* [pasvulkan](https://github.com/BeRo1985/pasvulkan). Vulkan header generator, OOP-style API wrapper, framework and prospective Vulkan-based game engine for Object Pascal.

* [DarkGlass](https://github.com/chapmanworld/DarkGlass). DarkGlass is a general purpose game engine written using Delphi.

* [JEDI-SDL](https://sourceforge.net/projects/jedi-sdl). Pascal headers for SDL from JEDI. Works with Delphi, Kylix, Free Pascal, Gnu Pascal and TMT Pascal.


## Communications ##


## Network
*Socket communication, network protocols, encodings, etc*

* [Internet Component Suite](http://www.overbyte.be/frame_index.html). Asynchronous-based library composed of various Internet components and applications. Clients/servers for TCP, UDP, raw sockets, FTP, SMTP, POP3, NNTP, HTTP, Telnet and more. Supports SSL and TLS with the help of OpenSSL. Also includes Mime Decoder, SHA1/MD4/MD5 hashes, DES encryption.

* [Indy](https://github.com/IndySockets/Indy). Network components for Delphi, C++Builder, Delphi.NET, and FreePascal
// *All-in-one network library based on blocking sockets and threads. Included in default RAD studio installation since 2006.*

* [Ararat Synapse](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://sourceforge.net/p/synalist). Pascal TCP/IP Library for Dephi, C++Builder, Kylix and FreePascal. Deals with network communication by means of blocking (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/synchronous) sockets or with limited non-blocking mode. This project not using asynchronous sockets! The Project contains simple low level non-visual objects for easiest programming without problems (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/no required multithread synchronisation, no need for windows message processing,...) Great for command line utilities, visual projects, NT services,...
// *TCP, UDP, ICMP, RAW; ICMP, DNS, SMTP, HTTP, SNMP, NTP, FTP, LDAP, NNTP, Telnet;  IPv6; SOCKS proxy; SSL/TLS (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/via OpenSSL or Windows CryptoApi); PING; character code transcoding; MIME coding and decoding; CRC16, CRC32, MD5 and HMAC-MD5.*

* [Internet Professional](http://sourceforge.net/projects/tpipro2010). Set of VCL components providing Internet connectivity for Borland Delphi & C++Builder. iPRO includes POP3, SMTP, NNTP, FTP, HTTP, Instant Messaging, & HTML viewer components, as well as components for low-level socket access.
// *Seems abandoned but contains pretty large set of features incl ICMP, POP, SMTP, HTTP, NNTP, NTP, FTP, SMTP; HTML parser and viewer; MIME utils; cookies, certificates, caching, encryption etc*

* [SynCrtSock](https://github.com/synopse/mORMot/blob/master/SynCrtSock.pas). Features several sockets and HTTP client-server classes, including a high-performance http.sys based server under Windows, and a new thread-pool powered socket server.
// *Also implements http.sys binding under Windows and cURL binding under nix*

* [TML Messaging Suite](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://www.libtml.org/docs/libtml-pascal). Network messaging library for rapid development of extensible and scalable interfaces. Based on the peer to peer standard protocol [BEEP (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Blocks Extensible Exchange Protocol)](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://www.beepcore.org), defined in [RFC3080](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://tools.ietf.org/html/rfc3080) and [RFC3081](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://tools.ietf.org/html/rfc3081). libTML is suitable for many use cases and communication patterns. Equipped with a type safe data API, TML can transport hierarchical data structures fast and reliable.
// *The libTML Object Pascal Components are not only a language binding to the core library but a complete set of non visual components to simplify the usage of libTML with Embarcadero RAD Studio and Lazarus.*

* [DMVCFramework](https://github.com/danieleteti/delphimvcframework). Popular and powerful framework for web solution in Delphi.

* [Delphi IOCP](https://github.com/ymofen/diocp-v5). Implements several network classes based on Windows IOCP technology. Socket, HTTP, Ntrip servers and clients.
// *Quite well documented and good styled code but Chinese only.*

* [delphi-aws-ses](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/monde-sistemas/delphi-aws-ses). Amazon Simple Email Service (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/AWS SES) library for Delphi applications.

* [delphi-slackbot](https://github.com/monde-sistemas/delphi-slackbot). Delphi library to send messages on [Slack](https://slack.com) using slackbot.

* [Kitto](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/nandod/kitto). Allows to create Rich Internet Applications based on a data model that can be mapped onto any database. The client-side part uses ExtJS (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/through the ExtPascal library) to create a fully AJAX application, allowing you to build standard and advanced data-manipulating forms in a fraction of the time. Kitto is aimed at Delphi developers that need to create web application without delving into the intricacies of HTML, CSS, Javascript or learning to use a particular library such as ExtJS, yet it allows access to the bare metal if required.

* [Daraja Framework](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/michaelJustin/daraja-framework). Lightweight HTTP server framework for Object Pascal (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Delphi 2009+ / Free Pascal 3.0). Implementing RESTful services is supported via the [daraja-restful](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/michaelJustin/daraja-restful) extension.

* [Alcinoe](#general-libraries). FTP/Http/NNTP/POP3/SMTP, ISAPI, WinInet Http/FTP clients.

* [Fundamentals Code Library](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/#general-libraries). Blocking TCP client/server, HTTP(https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/S) via SSL3/TLS1.0/TLS1.1/TLS1.2 (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/fully native).

* [mORMot](#general-libraries). RESTful ORM and SOA services via interfaces over high performance HTTP server, MVC/MVVM web sites

* [SDriver](https://github.com/andrea-magni/SDriver). Delphi wrapper for [Slack](https://slack.com) API.

* [Hprose for Delphi/Lazarus](https://github.com/hprose/hprose-delphi). High Performance Remote Object Service Engine. It is a modern, lightweight, cross-language, cross-platform, object-oriented, high performance, remote dynamic communication middleware. It is not only easy to use, but powerful. This project is the implementation of Hprose for Delphi/Lazarus.

* [TelegAPI](https://github.com/ms301/TelegAPI). Library for working with Telegram messenger Bot API in Delphi.

* [DelphiZeroMQ](https://github.com/grijjy/DelphiZeroMQ). Delphi implementation of ZeroMQ Majordomo protocol and CZMQ high level binding.

* [GrijjyFoundation](#general-libraries). IOCP/EPOLL sockets, socket pools, HTTP, HTTP/2, OpenSSL, ProtocolBuffers.

* [Rest-Dataware-Componentes](https://github.com/Rest-Dataware/RDW-Componente). Was created to facilitate the creation of CRUDs in the same model that we created applications for Client / Server Database. With REST DW, you no longer have to worry about creating SQL Insertion, Deletion, Read and Execution methods via Webservice; Simply add a RESTDataBase connection component and add a RESTClientSQL component that will already have your SQL solution fully functional as it did back in the day and with all the power of modern REST / JSON technology with data compression and everything the language can offer.

* [STOMP Client](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/danieleteti/delphistompclient). STOMP client for Embarcadero Delphi and FreePascal. The project can use INDY (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Delphi) or Synapse (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Delphi or FreePascal).

* [delphiXero](https://github.com/littleearth/delphiXERO). XERO cloud accounting API for Delphi.

* [BesaSoap](https://github.com/besasoftware/besasoap). The BesaSoap library is designed to help programmers develop faster and more native web service client applications. Represents C# or Java like native class support, nullable data types and custom attributes.

* [IndySoap](https://sourceforge.net/projects/indysoap). Open Source Library for implementing Web services using Delphi/CBuilder Compilers. IndySoap isn't tied to Indy for transport services, though Indy based transport services are included.


## Serial port

* [Synaser](http://sourceforge.net/p/synalist/code/HEAD/tree/trunk/synaser.pas). Library for blocking communication on serial ports. It is non-visual class as in Synapse, and programmer interface is very similar to Synapse.

* [Async Professional](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://sourceforge.net/projects/tpapro) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/[Newest](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/TurboPack/AsyncPro) and maintained version for recent compiler version only). Comprehensive communications toolkit for Embarcadero Delphi, C++Builder, & ActiveX environments. It provides direct access to serial ports, TAPI and the Microsoft Speech API (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/TTS/Speech recognition). It supports faxing, terminal emulation, VOIP, RAS dial & more.
// *Seems outdated (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/last update in 2011) but adapted to XE and should be easy to use in newer versions. The project is also very thoroughly documented. Second link points to an adapted version for newest compiler versions.*

* [TComPort](https://sourceforge.net/projects/comport). Delphi/C++ Builder serial communications components. It is generally easy to use for basic Serial Communications purposes.
// *Seems abandoned since 2011*


## GUI ##
*Visual components*

## Control packs
*Large sets of GUI controls*

* [Cindy components](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://sourceforge.net/projects/tcycomponents). Packages with 71 components: VCL controls (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/labels, buttons, panels, Edits, TabControls, StaticText) with features like background gradient, colored bevels, wallpaper, shadowText, caption orientation etc...

* [Orpheus](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://sourceforge.net/projects/tporpheus) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/[Newest](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/TurboPack/Orpheus) and maintained version for recent compiler version only). Award-winning UI toolkit for Borland Delphi & C++Builder. It contains over 120 components covering everything from data entry to calendars and clocks. Other noteworthy components include an Object Inspector, LookOut bar & report views.
// *Advanced edits, comboboxes, grids + component (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/de)serializers. GUI components look rather old-style, theme support might be limited. Package contains many demos but no docs seem available. Second link points to an adapted version for newest compiler versions.*

* [KControls](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://www.tkweb.eu/en/delphicomp/kcontrols.html). Control components. All controls have been written with the aim to become both cross-IDE compatible (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Delphi/C++Builder VCL and Lazarus LCL) and cross-platform compatible in Lazarus.
// *Most useful are TKGrid with its DB-aware heritage TKDBGrid — a very full-featured grid implementation incl. inplace editors. There's also hex editor, print preview, editors, labels, buttons etc.*

* [D.P.F Delphi Android](http://sourceforge.net/projects/dpfdelphiandroid) / [D.P.F Delphi iOS](http://sourceforge.net/projects/dpfdelphiios) native components. D.P.F Delphi Native Components, 100% iOS Performance and styles. Develop iPhone & iPad & iPod Touch applications with fast native performance and native styles. Use native Android controls and services. Fast native performance. Mixed with FM VCL controls. Can be quick updated with latest Android controls & features.

* [Essentials](https://github.com/TurboPack/Essentials). Contains 13 native VCL controls for Embarcadero Delphi and C++Builder. The controls include drop-down calendars and calculators, roll-up dialogs, 3-D labels, tiled backgrounds, scrolling messages, menu buttons, and more.

* [FreeEsVCLComponents](https://github.com/errorcalc/FreeEsVCLComponents). Free library of VCL components for Delphi and C++Builder. This new controls and components to improve the appearance applications and to better user experience. Components support visual styles and has modern style. All components has best support transparency, not flicker, and has support Interesting possibility for double buffering for TGraphicControl heirs.

* [SpTBXLib](https://github.com/SilverpointDev/sptbxlib). Add on package for Toolbar2000 components, it adds the following features: Skins, Unicode support, Custom painting events and many more.


## Single controls

* [EasyListView](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://code.google.com/p/mustangpeakeasylistview) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/seems abandoned, active fork on GH [here](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/TurboPack/MustangpeakEasyListview)). Part of VirtualShellTools for the Listview but can be used for a TListview Replacement that is faster and more customizable.
// *Feature-rich Listview implementing virtual (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/callback-based) MVC paradigm.*

* [VirtualTreeView](https://github.com/Virtual-TreeView/Virtual-TreeView). Treeview control built from ground up. Many years of development made it one of the most flexible and advanced tree controls available today.
// *Extremely flexible visual component implementing virtual (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/callback-based) MVC paradigm. Could be also used as a listview or grid. Used in RAD Studio GUI.*

* [Delphi Chromium Embedded](https://github.com/hgourvest/dcef3/commits/master). Embedding Chromium in Delphi, tested on Delphi 2010, XE, XE2, Delphi 7.
// *Several Chromium DLLs required*

* [TChromeTabs](https://github.com/norgepaul/tchrometabs). Comprehensive implementation of Google Chrome's tabs for Delphi 6 - Delphi 10.1 Berlin

* [TFrameStand](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/andrea-magni/TFrameStand). Easily use TFrame(https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/s) in your FireMonkey (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/FMX) applications to gain visual consistency though the whole user experience and easily add modern looking elements like effects and transitions.

* [TPrintPreview](https://github.com/landrix/TPrintPreview-for-Delphi). Print Preview Component for Delphi Vcl Win32/Win64

* [VolgaDB](https://sourceforge.net/projects/volgadb). Pretty customizable DBgrid for Delphi. TCustomGrid descendant. CheckBox, ComboBox column styles. Also includes TVolgaDBEdit that replaces TDBEdit, TDBComboBox, TDBLookupCombo, TDBLookupTree andTDBDatePicker in one component. TVolgaDBEdit may be DB-aware and non DB-aware.
// *Seems abandoned since 2013*

* [TTreeListView](http://github.com/benibela/treelistview). This component is a mix between TTreeView and TListView and can paint a tree whose nodes have additional information sorted in columns.

* [neTabControl](https://github.com/jkour/neTabControl). FireMonkey control for Delphi. It builds on the native TabControl and adds a number of features.

* [ATTabs](https://github.com/Alexey-T/ATTabs). Delphi/Lazarus component for lite tabs. OS independent, fully custom drawn.


## Editors

* [SynEdit](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://sourceforge.net/projects/synedit) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/[mirror at GitHub](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/TurboPack/SynEdit)). Syntax highlighting edit control, not based on the Windows common controls. SynEdit is compatible with both Delphi and Kylix

* [BCEditor](https://github.com/bonecode/BCEditor). Syntax highlighting edit control with code folding, minimap, external JSON highlighter and color scheme files, etc.
// *Very powerful and feature-rich component. Supports Delphi XE4..XE8, C++ Builder XE7, backport to XE available*


## Viewers

* [ATViewer](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://sourceforge.net/projects/atviewer) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/[mirror at GitHub](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/Alexey-T/ATViewer)). Delphi components to view various file types: text, binary, images, multimedia, webpages, etc.
// *Used in Universal Viewer software. Could be used to display hex dumps, features fast display of unlimited size files/streams. Supports Total Commander Lister plugins.*

* [ATImageMap](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://sourceforge.net/projects/atviewer/files/ATImageMap) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/[mirror at GitHub](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/Alexey-T/ATViewer)). Component designed to show many images (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/parts of the whole image) as a single map. For example, you may have array of images, 200 by X, and 100 by Y and control will show them as a single map. Component also allows to draw paths: each path consists of many lines, points, and icons.

* [HtmlViewer](https://github.com/BerndGabriel/HtmlViewer). Delphi/Lazarus HtmlViewer/FrameViewer.
// *Html visualiser supporting majority of tags, inline styles and CSS.*

* [SciDe](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/da-baranov/SciDe). [Sciter](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://sciter.com) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Embeddable HTML/CSS/script engine) wrapper for Delphi.

* [ATBinHex](https://github.com/Alexey-T/ATViewer). Viewer for files of unlimited size like in Total Commander.


## Other GUI

* [GMLib](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://code.google.com/p/gmlibrary) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Google Maps Library) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/seems abandoned, active fork on GH [here](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/bero/GMLibrary) and [here](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/cadetill/gmlib_v1)). Components for Delphi/C++ Builder that encapsulate the GoogleMaps API to administrate a map, markers, polygons, rectangles, polylines,... All objects that you can put into a map.

* [VCL Styles Utils](https://github.com/rruz/vcl-styles-utils). Collection of classes and style hooks, which extend, fix QC reports and add new features to the VCL Styles.
// *Collection of patches/enhancements that promote stock VCL style engine to a new level. Styling for Inno setup and NSIS also available.*

* [TaskbarListComponents](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/chaosben/theunknownones). Set of components designed as Delphi wrappers for the Windows 7 Taskbarlist Interfaces (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/e.g. ITaskbarlist3)
// *Requires JVCL*

* [TFireMonkeyContainer](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/vintagedave/firemonkey-container). Delphi VCL component to host a FMX HD or 3D form. It means you can embed a FireMonkey (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/FMX) form as a control in a VCL form, so you can design a FMX form and use it in your VCL app.

* [PascalSCADA](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://sourceforge.net/projects/pascalscada). Set of components (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/framework) for Delphi/Lazarus to make easy the development of industrial applications (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/HMI=Human Machine Interface/SCADA=System Control And Data Acquisition). It runs on Windows, Linux and FreeBSD.

* [Windows Ribbon Framework for Delphi](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/turbopack/ribbonframework). This Delphi library allows Delphi developers to use of the Windows Ribbon Framework in their Delphi applications. This library uses the native Windows library to implement the Ribbon functionality. It does not emulate the Ribbon user interface like other Delphi component sets do (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/or Delphi's built-in Ribbon emulation components).

* [DKLang](https://github.com/yktoo/dklang). DKLang Localization Package is a set of classes intended to simplify the localization of applications written in Delphi.

* [GNU Gettext for Delphi, C++ and Kylix](https://sourceforge.net/projects/dxgettext/). GNU GetText translation tools for Borland Delphi and Borland C++ Builder.

* [OpenWire](https://sourceforge.net/projects/openwireproject). The library allows writing advanced VCL and FireMonkey components for rapid codeless application development. The components developed with the library allow creation of complex applications with zero lines of program code.

* [SynTaskDialog](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/synopse/mORMot/blob/master/SynTaskDialog.pas). Implement TaskDialog window (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/native on Vista/Seven, emulated on XP)

* [AnyiQuack](https://github.com/WladiD/AnyiQuack). jQuery-like control animation framework.

* [TLanguages](https://github.com/albertodev01/TLanguages). Localization tool for VCL and FMX.


## Database ##

* [ZeosLib](http://sourceforge.net/projects/zeoslib). Set of database components for MySQL, PostgreSQL, Interbase, Firebird, MS SQL, Sybase, Oracle and SQLite.

* [Unified Interbase](http://sourceforge.net/projects/uib). Set of components to use Interbase, FireBird and YAFFIL. These components were born from the need to use Interbase, FireBird or Yaffil indifferently as fast as possible in a Multithreading environment, a Server for example.

* [ASQLite](https://github.com/remobjects/ASQLite3). Delphi SQLite set of DAC components from aducom software, based on their latest release for Delphi 2009, and updated to support newer editions of Delphi as included in RemObjects Data Abstract for Delphi.

* [TxQuery](https://github.com/ccy/txquery). TDataSet descendant component that can be used to query one or more TDataSet descendant components using SQL statements. It is implemented in Delphi 100% source code, no DLL required, because it implements its own SQL syntax parser and SQL engine.

* [Delphi-ORM](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/danieleteti/delphi-orm). Object-Relational Mapping for Delphi XE7, XE6, XE5, XE4, XE3 and XE2 (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Win32). Supports for FirebirdSQL, SQLServer and SQLite3.

* [delphimemcache](https://code.google.com/p/delphimemcache). Implements a thread safe client for memcached.
// *Requires Indy 10*

* [SynDB](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/synopse/mORMot) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/[docs](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://synopse.info/files/html/Synopse%20mORMot%20Framework%20SAD%201.18.html#TITL_126)). High performance direct access to SQLite3, Oracle, MSSQL, PostgreSQL, Firebird, MySQL, ODBC, OleDB, including remote HTTP connection and direct JSON support.

* [SynMongoDB](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/synopse/mORMot/blob/master/SynMongoDB.pas) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/[docs](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://blog.synopse.info/post/2014/05/07/MongoDB-database-access)). Offers direct low-level access to any MongoDB server, its custom data types, JSON or via `TDocVariant` custom variant document storage.

* [DSharp](https://bitbucket.org/sglienke/dsharp). Small library for providing data binding in Delphi. It does not require special components to data bind to properties. It also provides dependency injection, MVVM and more interesting utilities.

* [ghORM](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/leledumbo/ghORM). Object Relational Mapping unit to ease database access from Free Pascal, by abstracting the backend and simple data retrieval (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/with filtering), insertion and update.

* [tDBF](http://sourceforge.net/p/tdbf/code/HEAD/tree). Native dBASE III+, dBase IV and dBase 2k data access component for Delphi, BCB, Kylix, FreePascal. It allows you to create very compact database programs which don't need any special installer programs. The DB engine code is compiled right into your executable. 

* [Redis client](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/danieleteti/delphiredisclient) for Delphi 10.1 Berlin, Delphi 10 Seattle, XE8, XE7, XE6 and XE5 (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/should works also with older versions). This client is able to send all Redis commands and read the response using an internal parser.

* [QDAC3](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://blog.qdac.cc/?page_id=139) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/SVN: svn://www.qdac.cc/QDAC3). Stands for quick data access components. Useful units such as QJson (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/easy to use json unit), QWorker(https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/job delivery) etc.
// *Description and comments in Chinese, author is not good at English. Haven't tested this library by myself.*

* [InstantObjects](https://sourceforge.net/projects/instantobjects). Integrated framework for developing object-oriented business solutions in Delphi. The framework provides the foundation for the development process as well as the engine that powers the final application. InstantObjects offers: Model realization in the Delphi IDE via integrated two-way tools; Object persistence in the most common relational databases or flat XML-based files; Object presentation via standard data-aware controls.

* [Alcinoe](#general-libraries). Firebird/MySQL/SQLite3/Memcached/MongoDb/SphinxQL.

* [SynBigTable](https://github.com/synopse/mORMot/blob/master/SynBigTable.pas). Class used to store huge amount of data with fast retrieval.

* [tiOPF](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/graemeg/tiopf). Object Persistent Framework written in Object Pascal, for use with Delphi and Free Pascal (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/FPC) compilers. tiOPF simplifies the mapping of an object oriented business model into a relational database. Persistence layers are available for Firebird, Oracle, MS SQL Server, MySQL, PostgreSQL, SQLite, NexusDB, XML, CSV, TAB, Remote (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/via HTTP) and many more. It also allows you to use your choice of database connection components, like IBX, dbExpress, DOA, SqlDB, FBLib etc.

* [hcOPF](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://sourceforge.net/projects/larryhengensopf). Object Persistent Framework written in Embarcadero's Delphi (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Object Pascal). This Value Type Framework provides a base class (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/ThcObject) composed of attribute objects that can be automatically persisted to an object store (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/normally an RDBMS).

* [Marshmallow](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://bitbucket.org/soundvibe/marshmallow/wiki/Home). Object-Relational Mapping for Delphi XE7, XE6, XE5, XE4, XE3 and XE2 (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Win32) inspired by .NET micro ORM's (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/mostly by PetaPoco) and Java Hibernate. Developed  by Linas Naginionis. Supports SQLite, Sybase ASA, SQL Server, Firebird, Oracle, MySQL, PostgreSQL, MongoDB. Uses [Spring](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://code.google.com/p/delphi-spring-framework/) Framework. In active development.

* [DelphiCassandra](https://github.com/grijjy/DelphiCassandra). Delphi driver classes to communicate with Cassandra database.

* [DelphiCouchbase](https://github.com/grijjy/DelphiCouchbase). Delphi driver classes to communicate with Couchbase database.

* [DelphiMongoDB](https://github.com/grijjy/DelphiMongoDB). Delphi driver classes to communicate with MongoDB database.

* [QuickORM](https://github.com/exilon/QuickORM). QuickORM is a simple RestServer and Restclient based on mORMot framework. Provides a fast implementation of client-server applications in few minutes.


## Scripting ##
*Using script engine in your applications*

* [Pascal Script](https://github.com/remobjects/pascalscript). Free scripting engine that allows you to use most of the Object Pascal language within your Delphi or Free Pascal projects at runtime. Written completely in Delphi, it is composed of a set of units that can be compiled into your executable, eliminating the need to distribute any external files. Pascal Script started out as a need for a good working script, when there were none available at the time.

* [DWScript](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://bitbucket.org/egrange/dwscript). Object-oriented scripting engine for Delphi based on the Delphi language, with extensions borrowed from other Pascal languages (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/FreePascal, Prism, etc.). It introduces a few Pascal language extensions of its own as well.

* [Delphi-Javascript](https://code.google.com/p/delphi-javascript). Javascript engine for delphi based on Mozilla's Spidermonkey.
// *Spidermonkey DLL required*

* [Blaise](http://sourceforge.net/projects/blaise). Open-source object-oriented scripting language. Language features: Object-oriented; Unicode support; Optional typing, ie dynamic or static typing; Richly typed; Higher-level mathematics support, for example Complex numbers, Rational numbers and Matrices; Virtual Machine architecture; Co-routines; Familiar language syntax, influenced by Object Pascal, Python and Ada.

* [SpiderMonkey](https://github.com/synopse/mORMot/blob/master/SynSM.pas). Binding for Mozilla JavaScript engine, including JIT and multi-threading, with easy objects access via Delphi variants.
// *Spidermonkey DLL required*

* [BESEN](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/BeRo1985/besen). Complete ECMAScript Fifth Edition Implemention in Object Pascal, which is compilable with Delphi >=7 and Free Pascal >= 2.5.1 (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/maybe also 2.4.1).

* [Python for Delphi (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/P4D)](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/pyscripter/python4delphi). Set of free components that wrap up the Python dll into Delphi and Lazarus (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/FPC). They let you easily execute Python scripts, create new Python modules and new Python types. You can create Python extensions as dlls and much more

* [CrystalLUA](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/d-mozulyov/CrystalLUA). Lua binding (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Delphi6-2007).
// *LUA DLL required*

* [lua4delphi](https://github.com/danieleteti/lua4delphi). Delphi binding for Lua 5.1 language.
// *LUA DLL required*

* [chakracore-delphi](https://github.com/tondrej/chakracore-delphi). Delphi and Free Pascal bindings and classes for Microsoft's ChakraCore JavaScript engine library.

* [VerySimple.Lua](https://github.com/Dennis1000/verysimplelua). Lua Wrapper for Delphi XE5-D10.1 which automatically creates OOP callback functions for Delphi <-> Lua.
// *LUA DLL required*


## Non-visual Classes/Utils ##


## Compression

* [FWZip](https://github.com/AlexanderBagel/FWZip). Classes to work with Zip archives using Store and Deflate methods, supports ZIP64, DataDescryptors, PKWARE encryption, NTFS attributes, Utf8 in filenames.
// *Uses stock ZLIB.obj that gets compiled into binary*

* [Abbrevia](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://sourceforge.net/p/tpabbrevia) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/[Newest](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/TurboPack/Abbrevia) and maintained version for recent compiler version only). Advanced data compression toolkit for Delphi and C++Builder. Supports PKZIP, Microsoft CAB, tar, gzip, and bzip2 archives, and can create self-extracting executables. On Windows it also provides Delphi wrappers for the LZMA, Bzip2, and WavPack SDKs, and PPMd decompression. Abbrevia also has several visual controls that simplify displaying and manipulating archives, including treeview and listview components. Features: Unicode filenames in all archive formats; Decompress most .zipx and legacy (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/PKZIP v1) zips; ZIP64 support for archives larger than 2GB; Spanned and split zip archives; Cross-platform (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Windows, OS X, and Linux); No DLLs required; Includes COM component; Extensive documentation
// *Second link points to an adapted version for newest compiler versions.*

* [SynLZ SynLZO SynZip PasZip](https://github.com/synopse/mORMot). Several high speed compression units, featuring ZIP/LZ77 Deflate/Inflate, LZO and SynLZ algorithm, in pascal and optimized assembler.

* [Delphi zlib](http://www.base2ti.com/?id=delphi.zlib). Wrapper for zlib.obj originally used by Borland. Delphi up to XE3 supported.

* [DIUcl](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://www.yunqa.de/delphi/products/ucl/index). DIUcl is a lossless compression library with extremely fast and small (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/200 bytes only!) ASM decompressor. Compression times and ratios are similar to those of deflate/zip and bzip2. Delphi port of the popular UCL Compression Library, which is also used by the popular and well known UPX Ultimate Packer for eXecutables.


## Encryption

* [Delphi Encryption Compendium (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/DEC)](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/winkelsdorf/DelphiEncryptionCompendium/releases). Cryptographic library for Delphi & C++ Builder. Symmetric cryptographic functions: Blowfish, Twofish, IDEA, Cast128, Cast256, Mars, RC2, RC4, RC5, RC6, Rijndael / AES, Square, SCOP, Sapphire, 1DES, 2DES, 3DES, 2DDES, 3DDES, 3TDES, 3Way, Gost, Misty, NewDES, Q128, SAFER, Shark, Skipjack, TEA, TEAN; Block cipher modes of operation: CTSx, CBCx, CFB8, CFBx, OFB8, OFBx, CFSx, ECBx; Hashes: MD2, MD4, MD5, RipeMD128, RipeMD160, RipeMD256, RipeMD320, SHA, SHA1, SHA256, SHA384, SHA512, Haval128, Haval160, Haval192, Haval224, Haval256, Tiger, Panama, Whirlpool, Whirlpool1, Square, Snefru128, Snefru256, Sapphire.
// *No updates since 2010, some activity started at 2018 in **development** branch. Anyway features list so huge that it couldn't be ignored*

* [LockBox](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://sourceforge.net/projects/tplockbox) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/[Newest](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/TurboPack/LockBox3) and maintained version for recent compiler version only). Delphi library for cryptography. Currently supported Delphi XE6. It provides support for AES, DES, 3DES, Blowfish, Twofish, SHA2 (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/including the new SHA-512/224 & SHA-512/256), MD5; ECB, CBC, CFB8, CFB, CTR, ECB, OFB, PCBC chaining modes, RSA digital signature and verification. Has interface to OpenSSL library.
// *Check out [this](https://github.com/jarto/lockbox2) page as well for alternative version.*

* [SynCrypto](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/synopse/mORMot/blob/master/SynCrypto.pas). Fast cryptographic routines (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/hashing and cypher), implementing AES, XOR, RC4, ADLER32, MD5, SHA1, SHA256 algorithms, optimized for speed (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/tuned assembler and VIA PADLOCK optional support).

* [TForge](https://bitbucket.org/sergworks/tforge). Open-source crypto library written in Delphi, compatible with Free Pascal Compiler. MD5, SHA1, SHA256, CRC32, Jenkins-One-At-Time, HMAC, PBKDF1, PBKDF2, AES, DES, RC4, RC5, Salsa20.

* [Spring4D](#general-libraries). CRC, DES, MD5, SHA

* [Fundamentals Code Library](#general-libraries). Hashes: XOR, CRC, Adler, MD5, SHA, secure keyed MD5/SHA, etc; Cipher: AES, DES, FUNE, RC2/4, RSA.

* [Alcinoe](#general-libraries). AES, Blowfish, MD5, SHA, secure keyed MD5/SHA.

* [DCPcrypt (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/fork #1)](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://sourceforge.net/projects/dcpcrypt), [DCPcrypt (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/fork #2)](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://bitbucket.org/wpostma/dcpcrypt2010). Suite of cryptographic components for Delphi.

* [HashLib4Pascal](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/Xor-el/HashLib4Pascal). Delphi/FreePascal compatible library that provides an easy to use interface for computing hashes and checksums of strings (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/with a specified encoding), files, streams, byte arrays and untyped data to mention but a few. It also supports Incremental Hashing.

* [CRC/Hash](http://www.wolfgang-ehrhardt.de/crchash_en.html). Pascal / Delphi source and binary files related to CRC, hash, and HMAC calculations. CRC, Adler, BJ lookup, MD5, SHA, Whirlpool, Blake

* [Crypto](http://www.wolfgang-ehrhardt.de/crypt_en.html). Several cipher algorithms: the 128-bit block ciphers AES and Twofish, the 64-bit block cipher Blowfish, and the stream ciphers Salsa20/XSalsa20/ChaCha and Sosemanuk. 


## XML/JSON/YAML

* [OmniXML](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/mremec/omnixml). XML parser written in Delphi. Full support for Document Object Model (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/DOM) Level 1 specification; Supports Extensible Markup Language (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/XML) 1.0 (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Second Edition) specification; Has built-in support for different code pages (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/main 8-bit code pages, UTF-8, UTF-16); Is compatible with MS XML parser; Fast parsing even large and highly structured documents; Includes helper functions to ease processing XML documents; Simplified XPath support.

* [SAX for Pascal](http://sourceforge.net/projects/saxforpascal). Designed to implement the Simple API for XML Parsing in Pascal/Delphi.
// *Callback-based XML parser, useful for processing huge XML streams. Abandoned since 2004 but is almost the only SAX implementation available.*

* [KDS XML](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://sourceforge.net/projects/kdsxml). Class library for streamed parsing, validating and generating XML. It is written in Object Pascal/Delphi and works on Win32 (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Delphi) and Linux (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Kylix). Parts of it depend on the SAX for Pascal interface specifications.
// *Seems dead.*

* [XML Partner](http://sourceforge.net/projects/tpxmlpartner). Helps add the power of XML to Borland Delphi, C++ Builder, and Kylix projects through native, easy to use VCL and CLX components. These powerful components simplify the process of creating, modifying, and parsing XML data documents.
// *Seems dead, check out [this](http://www.songbeamer.com/delphi) page for probably newer version.*

* [Open XML](http://www.philo.de/xml/downloads.shtml). Provides a wide range of methods, components and foundation classes. It can be used for Win32/Kylix as well as for .NET development.

* [SuperObject](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/hgourvest/superobject). Parser/writer for JSON data format. This toolkit is designed to work with Delphi and FreePascal (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/win32, win64, linux32, linux64, MacOSX Intel). Supports reading/writing XML as well.

* [Libxml2 for pascal](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://sourceforge.net/projects/libxml2-pas). Pascal units accessing the popular XML API from Daniel Veillard. This should be usable at least from Kylix and Delphi, but hopefully also from other Pascal compilers (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/like freepascal).

* [NativeXml](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://code.google.com/p/simdesign). This component contains a small-footprint Object Pascal (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Delphi) XML implementation that allows to read and write XML documents. You basically only need one unit and you can simply add it to the "uses" clause. You can use this software to read XML documents from files, streams or strings. The load routine generates events that can be used to display load progress on the fly. You can also use it to create and save XML documents.

* [Delphi-XmlLite](https://github.com/the-Arioch/Delphi-XmlLite). Header translation for Microsoft XmlLite. XmlLite is a native C++ implementation of .NET XmlReader+Writer for stream-based, forward-only XML parsing and creation. XmlLite.dll is required. It is included with all new versions of Windows, and service packs for old versions. XmlReader's pull-based interface is cleaner to use than SAX's event-based interface.
// *Seems abandoned and reported to be somewhat buggy.*

* [Chimera](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://bitbucket.org/sivv/chimera). Open Source (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/MIT License) library for Delphi XE2 which provides a fast and cross platform JSON generator/parser (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/serializer/deserializer) under a license that doesn't suck.

* [SynCommons](https://github.com/synopse/mORMot/blob/master/SynCommons.pas). High speed JSON library, using `TDocVariant` custom variant type for storage and access.

* [SynCrossPlatformJSON](https://github.com/synopse/mORMot/blob/master/CrossPlatform/SynCrossPlatformJSON.pas). High speed cross-platform JSON library, using `TJSONVariant` custom variant type for storage and access.

* [Json Data Objects](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/ahausladen/JsonDataObjects). This Delphi unit contains a JSON parser that supports Delphi 2009-10Seattle and the platforms Win32, Win64 and ARM Android (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/MacOS and iOS may work).

* [TinyJSON](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://sourceforge.net/projects/tinyjson). This is a small (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/about 1600 lines of code) unit for Delphi, which realizes parsing and generating JSON format. Can be used in combination with FastMM and FastCode for even faster speed.

* [JSON delphi library](http://sourceforge.net/projects/lkjson). This is a delphi library implementing JSON. Lightweight and fast.

* [dwsJSON](https://bitbucket.org/egrange/dwscript/src/b9f99d4b8187defac3f3713e2ae0f7b83b63d516/Source/dwsJSON.pas?at=master). dwsJSON is a unit that supports JSON parsing/creating, it's part of DWScript but relatively "standalone", in that if you add it in your Delphi (or FPC) projects, it won't pull the whole of DWScript library, and thus can be used anywhere you need.

* [Fundamentals Code Library](#general-libraries). JSON, XML.

* [Alcinoe](#general-libraries). XML/JSON Parser.

* [delphi-yaml](https://bitbucket.org/OCTAGRAM/delphi-yaml). Delphi 7 compatible bindings for libyaml, YAML parser and emitter library implemented in C. Four layers of bindings are proposed.

* [GrijjyFoundation](#general-libraries). JSON/BSON.

* [VerySimpleXML](https://github.com/Dennis1000/verysimplexml). Lightweight, one-unit, cross-platform XML reader/writer for Delphi 2010 - 10.2.2 Tokyo

* [XSuperObject](https://github.com/onryldz/x-superobject). Delphi Cross Platform Rapid JSON

## Language
*Tools for Pascal and other languages*

* [Next Delphi Yacc & Lex](https://github.com/RomanYankovsky/ndyacclex). Parser generator toolset for Delphi.

* [Abstract Syntax Tree Builder](https://github.com/RomanYankovsky/DelphiAST). With DelphiAST you can take real Delphi code and get an abstract syntax tree. One unit at time and without a symbol table though.

* [Castalia-Delphi-Parser](https://github.com/jacobthurman/Castalia-Delphi-Parser). These files make up a hand-written high speed parser for the Object Pascal dialect known as "Delphi". The original work was done by Martin Waldenburg in the late 1990s, and the project was abandoned sometime before 2003, when I found the code and began working on it.  I have kept it updated as necessary to work with my project, called "Castalia".

* [CrossPascal](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/BeRo1985/crosspascal). Aims to be a Delphi 7 compatible cross-platform source-to-source compiler (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/together with the new unicode string types from XE3 but where ansistring is still the default string type for to be still Delphi 7 compatible) which generates intermediate C code.
// *Quite interesting project though seems abandoned*


## Memory managers
*Libraries that implement dynamic memory allocation*

* [FastMM](https://github.com/pleriche/FastMM4). Lightning fast replacement memory manager for Embarcadero Delphi Win32 and Win64 applications that is not prone to memory fragmentation, and supports shared memory without the use of external .DLL files.
// *Used as stock memory manager since 2006 but in simplified version. Provides powerful memory leak/corruption detection instruments.*

* [ScaleMM](https://github.com/andremussche/scalemm). Fast scaling memory manager for Delphi

* [BrainMM](https://github.com/d-mozulyov/BrainMM). Extremely fast memory manager for Delphi.
// *Advanced memory allocation functions for faster aligned operations.*


## System
*Low-level helper stuff: memory, threading etc*

* [OmniThreadLibrary](https://github.com/gabr42/OmniThreadLibrary). Simple to use threading library for Delphi.
// *Easy integration of async processes in your app*

* [Delphi Detours Library](https://github.com/mahdisafsafi/delphi-detours-library). Library allowing you to hook Delphi functions and object methods and Windows API functions. It provides an easy way to insert and remove hook.
// *Supports x64, calling original functions, multi hooks, COM/Interfaces/win32api, object methods hooking, fully thread-safe, Delphi 7/2005-2010/XE-XE7 & Lazarus/FPC, 64 bit address is supported.*

* [MemoryModule](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/Fr0sT-Brutal/Delphi_MemoryModule). With the MemoryModule engine you can store all required DLLs inside your binary to keep it standalone. Additional hook units allow transparent using of MM engine thus allowing switching MM/WinAPI loading as well as enabling 3rd party dynamic-load DLL interfaces that are unaware of MM (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/tested with Interbase Express components and Firebird client library). MemoryModule is a Pascal port of Joachim Bauch's C MemoryModule.

* [DirectoryWatcher](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/Wosi/DirectoryWatcher). Watch changes in directories on different platforms (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Windows/Linux/Mac OS).


## Template
*Engines to generate text output based on templates*

* [SynMustache](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/synopse/dmustache). Delphi implementation of the Mustache template language, supporting Delphi 6 up to Delphi 10 Seattle (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/and FPC/Lazarus compilation).

* [Delphi Template Engine](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://sourceforge.net/projects/delphi-templeng). Template engine designed to be used as a library in Delphi (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/mainly Delphi 7) applications, allowing developers to use templating on their software with no worry about implementing it.


## Logging

* [Log4d](https://github.com/landrix/Log4d-for-Delphi). Implementation of logging system for Delphi, based on Log4j.

* [TraceTool](http://tracetool.sourceforge.net/). C#, C++, Delphi, ActiveX and Java trace framework and a trace viewer.

* [LoggerPro](https://github.com/danieleteti/loggerpro). A modern and pluggable logging framework for Delphi.

* [SynLog](https://github.com/synopse/mORMot/blob/master/SynLog.pas). Logging functions used by Synopse projects.

* [slf4p](https://github.com/michaelJustin/slf4p). A simple logging facade with support for LazLogger, Log4D, and other logging frameworks.

* [GrijjyCloudLogger](https://github.com/grijjy/GrijjyCloudLogger). Remote logging tool that allows you to send log messages over the Intranet or Internet from Windows, Linux, iOS, Android and macOS devices to a viewer running on Windows. Besides sending messages along with any data, it has numerous features including custom live watches, remote live views of objects, tracking live memory usage, object allocations, growth leaks and more.

* [QuickLogger](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/exilon/QuickLogger). Delphi/freepascal/.NET (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Windows/Linux) library for logging on files, console, memory, email, rest, telegram, slack, eventlog, redis, ide debug messages and throw events..


## Math

* [Big Decimal Math](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/benibela/bigdecimalmath). This unit provides a arbitrary precision BCD float number type. It can be used like any numeric type and supports: At least numbers between 10-2147483647 to 102147483647 with 2147483647 decimal digit precision; All standard arithmetic and comparison operators; Rounding functions (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/floor, ceil, to-even, ..); Some more advanced operations, e.g. power and sqrt.

* [TIntX](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/Xor-el/IntXLib4Pascal). Pascal port of IntX arbitrary precision Integer library with fast, about O(https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/N * log N) multiplication/division algorithms implementation. It provides all the basic arithmetic operations on Integers, comparing, bitwise shifting etc. It also allows parsing numbers in different bases and converting them to string, also in any base. The advantage of this library is its fast multiplication, division and from base/to base conversion algorithms. all the fast versions of the algorithms are based on fast multiplication of big Integers using Fast Hartley Transform which runs for O(https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/N * log N * log log N) time instead of classic O(https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/N^2).

* [DelphiBigNumberXLib](https://github.com/Xor-el/DelphiBigNumberXLib). Arbitrary Precision Library for Delphi with Support for Integer and Floating Point Computations.

* [FastMath](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/neslib/FastMath). Delphi math library that is optimized for fast performance (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/sometimes at the cost of not performing error checking or losing a little accuracy). It uses hand-optimized assembly code to achieve much better performance then the equivalent functions provided by the Delphi RTL.
// *Floating-point, vector, matrix operations.*

* [MPArith](http://www.wolfgang-ehrhardt.de/misc_en.html#mparith). Multi precision integer, rational, real, and complex arithmetic.

* [AMath](http://www.wolfgang-ehrhardt.de/misc_en.html#amath) and [DAMath](http://www.wolfgang-ehrhardt.de/misc_en.html#damath). Accurate mathematical methods without using multi precision arithmetic and double precision accurate mathematical methods without using multi precision arithmetic or assembler respectively.


## Other non-visual

* [TRegExpr](https://github.com/ashumkin/RegExpr). Easy to use and powerful tool for sophisticated search and substitutioning and for template-based text input check.
// *Abandoned since 2004 but unlike stock RAD Studio implementation doesn't use PCRE obj files that add dependency on msvcrt.dll*

* [FLRE](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/BeRo1985/flre). FLRE (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/ F ast L ight R egular E xpressions) is a fast, safe and efficient regular expression library, which is implemented in Object Pascal (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Delphi and Free Pascal) but which is even usable from other languages like C/C++ and so on.

* [OnGuard](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://sourceforge.net/projects/tponguard) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/[Alternate](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/TurboPack/OnGuard-VCL) and maintained version for recent compiler version only). Library to create demo versions of your Borland Delphi & C++Builder applications. Create demo versions that are time-limited, feature-limited, limited to a certain number of uses, or limited to a certain # of concurrent network users.
// *Second link points to an adapted version for newest compiler versions.*

* [StringSimilarity](https://github.com/chaosben/theunknownones). Package designed for some fuzzy and phonetic string comparison algorithms. So far implemented are the following algorithms: DamerauLevenshtein, Koelner Phonetik, SoundEx, Metaphone, DoubleMetaphone, NGram, Dice, JaroWinkler, NeedlemanWunch, SmithWatermanGotoh, MongeElkan.

* [PubSub Chimera](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://code.google.com/p/pubsubchimera). Open Source (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/MIT License) library for Delphi which provides a fast and cross platform PubSub and Message Queue implementation under a license that doesn't suck.

* [DuckDuckDelphi](https://code.google.com/p/duckduckdelphi). Adds simple duck typing to Delphi Objects and provides an RTTI helper class to simplify many common RTTI tasks.

* [byterage](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/quartexNOR/byterage). Object pascal class library designed to remove some of the limitations of streams. The framework is very simple to use, with only one common ancestor class (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/TBRBuffer) which defines a set of storage agnostic mechanisms for allocating, scaling, inserting, deleting and otherwise manipulating a segment of raw binary data.

* [stateless](https://github.com/SirRufo/stateless). Simple library for creating state machines in Delphi code.

* [GenericTree](https://github.com/davidberneda/GenericTree). Delphi implementation of a generic Tree structure.

* [Delphi Event Bus](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/spinettaro/delphi-event-bus) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/for short DEB). Event Bus framework for Delphi.

* [DelphiEventBus](https://github.com/BitecSPB/DelphiEventBus). Yet another Event Bus framework for Delphi, with annotations and rich  event filtering.

* [DHibernate](https://github.com/thecocce/delphi-hibernate). Object Persistent Framework based on Hibernate and NHibernate for Delphi.
// *Abandoned since 2012*

* [UniConv](https://github.com/d-mozulyov/UniConv). Universal text conversion library is a universal quick and compact library intended for conversion, comparison and change of the register of text in concordance with the latest standards of the Unicode Consortium. The librarys function greatly resembles ICU, libiconv and Windows.kernel which are de facto standard for popular operating systems.

* [CachedBuffers](https://github.com/d-mozulyov/CachedBuffers). The library is irreplaceable for the tasks of sequential data reading or writing, especially if the requirements for the performance are increased and there are much data.

* [CachedTexts](https://github.com/d-mozulyov/CachedTexts). Powerful and compact cross-platform library aimed at parsing and generating of text data with the maximum possible performance. Depends on the two other libraries: CachedBuffers and UniConv.

* [ZEXMLSS](https://github.com/Avemey/zexmlss). Lazarus/Delphi component for read/write ods, excel xml, xlsx.

* [PasMP](https://github.com/BeRo1985/pasmp). Parallel-processing/multi-processing library for Object Pascal.

* [TCommandLineReader](https://github.com/benibela/rcmdline). This unit provides an advanced, platform-independent command line parser for Lazarus and Delphi. It checks for allowed options, automatically prints a help with a list of all of them, and - contrary to the parser in the rtl - behaves the same on Windows and Linux.

* [ICU4PAS](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://www.crossgl.com/icu4pas/index.html). Object Pascal, cross platform, Direct Class Wrapper over the mature and widely used set of C/C++ ICU libraries providing Unicode support, software internationalization (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/i18n) and globalization (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/g11n), giving applications the same results on all platforms. You can use it on Windows with Delphi and FreePascal and on Linux with Kylix and FreePascal.
// *Hadn't been updated since 2007 but ICU interface probably remains the same...*

* [CommandLineParser](https://github.com/VSoftTechnologies/VSoft.CommandLineParser). Simple Command Line Options Parser - spawned from the DUnitX Project.

* [GpCommandLineParser](https://github.com/gabr42/GpDelphiUnits/blob/master/src/GpCommandLineParser.pas). Attribute based command line parser.

* [GpDelphiUnits](https://github.com/gabr42/GpDelphiUnits). Collection of useful Delphi units. Various TList descendants, TList-compatible, and TList-similar classes. Dynamically allocated, O(1) enqueue and dequeue, threadsafe, microlocking queue. Interface to 64-bit file functions with some added functionality. String hash, table and dictionary. Collection of Win32/Win64 wrappers and helper functions. Time Zone Routines. Embedded file system.

* [BaseNcodingPascal](https://github.com/Xor-el/BaseNcodingPascal). Library for encoding of binary data into strings using base32, base85, base128 and other algorithms for FPC and Delphi.

* [ByteSizeLibPascal](https://github.com/Xor-el/ByteSizeLibPascal). TByteSize is a utility "record" that makes byte size representation in code easier by removing ambiguity of the value being represented.

* [EmailValidationPascal](https://github.com/Xor-el/EmailValidationPascal). Simple Class for Validating Email Address Syntax in Pascal/Delphi.

* [PRNG](http://www.wolfgang-ehrhardt.de/misc_en.html#prng). Seven fast pseudo random number generators with period lengths much greater than Pascal's random function. All are implemented with context records, therefore several independent generators can be used simultaneously, they are not cryptographically secure. In addition there are three cryptographic generators.

* [CSV File and String Reader](https://www.codeproject.com/Tips/783493/Delphi-CSV-File-and-String-Reader-Classes). TnvvCSVFileReader and TnvvCSVStringReader are light weighted and fast classes that resemble unidirectional data set.

* [HTMLBuilder](https://github.com/guitorres/htmlbuilder). Build simplified html with pascal code.

* [Marvin.IA](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/marvinbraga/Marvin.IA). Machine learning collection of object-oriented Pascal primitives (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/only interfaces and classes).


## OS ##
*Tools that help dealing with OS-specific internals*

* [GLibWMI](http://sourceforge.net/projects/glibwmi). Component Library for Delphi that encapsulate the classes for access to WMI of Windows in a set of VCL. BiosInfo, PrinterInfo, DiskInfo,... Allow access WMI Classes: WIN32_Bios, WIN32_Printers, WIN32_DiskDrive.

* [MemoryMap](https://github.com/AlexanderBagel/ProcessMemoryMap/tree/master/MemoryMap). Set of classes to get all the info about a memory of a running process.

* [The new Drag and Drop Component Suite](https://github.com/DelphiPraxis/The-Drag-and-Drop-Component-Suite-for-Delphi). VCL component library that enables your Delphi and C++Builder applications to support COM based drag and drop and integrate with the Windows clipboard.

* [TSMBIOS](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/RRUZ/tsmbios). Allows access the System Management BIOS (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/SMBIOS) using the Object Pascal language (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Delphi or Free Pascal). The SMBIOS (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/System Management BIOS) is a standard developed by the DMTF. The information stored in the SMBIOS includes devices manufacturer, model name, serial number, BIOS version, asset tag, processors, ports and device memory installed.

* [VersionInfo for Delphi](http://melander.dk/articles/versioninfo). The library makes it very easy to read values from the Version Info resource of Windows executables and DLLs. Optionally extends the TApplication class with a version info property via class helper.

* [Magenta Systems WMI and SMART Component](http://www.magsys.co.uk/delphi/magwmi.asp). Contains WMI, SMART and SCSI PassThrough functions, of particular use for getting hard disk information and configuring network adaptors, but also for many other general uses. MagWMI provides general view access to any WMI information using SQL like commands, and also a number of dedicated function relating to TCP/IP configuration, such as setting the adaptor IP addresses, the computer name, domain/workgroup, BIOS and disk drive information.

* [madKernel](http://help.madshi.net/madKernel.htm). The package is about Kernel Objects for the biggest part. The most important object types are wrapped up in  interfaces, utilizing all the specific kernel32 APIs. Has interface wrappers for: Events, Mutexes, Threads, Processes, Windows, Modules, Tray Icons, shared memory buffers.
// *Free with source for non-commercial usage (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/only) with some [conditions](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://help.madshi.net/License.htm). Available to download as part of `madCollection` installer. Pretty well documented. Requires `madBasic` package.*

* [madSecurity](http://help.madshi.net/madSecurity.htm). The package makes it easily possible to handle Shares and other Security Objects like file security or registry security. To be able to do so, this package also features functionality around Accounts and ACEs and ACLs.
// *Free with source for non-commercial usage (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/only) with some [conditions](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://help.madshi.net/License.htm). Available to download as part of `madCollection` installer. Pretty well documented. Requires `madBasic` package.*

* [madShell](http://help.madshi.net/madShell.htm). The package implements often needed shell functionality, beginning with Special Folders like the "Windows" folder or the "Program Files" folder, continuing with Shell ID Lists, Shell Objects and Shell Events. Then you'll find functionality around ShortCuts/ShellLinks and finally everything about Display Modes.
// *Free with source for non-commercial usage (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/only) with some [conditions](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://help.madshi.net/License.htm). Available to download as part of `madCollection` installer. Pretty well documented. Requires `madBasic` package.*


## Report generating ##

* [Report Manager](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://reportman.sourceforge.net/). Report manager is a reporting application (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Report Manager Designer) and a set of libraries and utilities to preview, export or print reports. Include native .Net and Delphi/C++Builder libraries, ActiveX component and also standard dynamic link library for use in any language like GNU C.

* [FortesReport](https://github.com/fortesinformatica/fortesreport-ce). The FortesReport is a powerful report generator available as a package of components for Delphi.


## Unit Testing ##

* [DUnitX](https://github.com/VSoftTechnologies/DUnitX). New test framework, taking ideas from DUnit, NUnit and other test frameworks. It is designed to work with Delphi 2010 or later, it makes use of language/RTL features that are not available in older versions of Delphi.

* [DUnit](http://dunit.sourceforge.net). Unit Testing Framework, that has been the standard testing framework for years, the Delphi IDE now ships with this library.
// *Included since XE, deprecated since XE8 in favor of DUnitX; seems abandoned.*

* [DUnit2](http://dunit2.sourceforge.net). Fork of the DUnit Project that adds several new features.
// *Seems abandoned, lacks some features from last DUnit version.*

* [DelphiSpec](https://github.com/RomanYankovsky/DelphiSpec). Library for running automated tests written in plain language. Because they're written in plain language, they can be read by anyone on your team. Because they can be read by anyone, you can use them to help improve communication, collaboration and trust on your team.

* [Delphi-Mocks](https://github.com/VSoftTechnologies/Delphi-Mocks). Simple mocking framework for Delphi XE2 or later. Allow you to mock both classes and interfaces for testing. 

* [DUnit-XML](https://github.com/VSoftTechnologies/DUnit-XML). Test runner that allows DUnit Tests to output NUnit compatible XML.

* [Smoketest](https://github.com/deltics/delphi.libs/tree/master/smoketest). Framework for writing tests and performance benchmarks using the Delphi language for Microsoft Windows. It has been tested on all versions of Delphi from 7 thru to 2010.

* [SynTests](https://github.com/synopse/mORMot/blob/master/SynTests.pas). Unit test functions including mocks and stubs.

* [OpenCTF](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://openctf.sourceforge.net). Test framework add-on for Embarcadero Delphi which performs automatic checks of all components in Forms (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/or DataModules). It provides an easy way to build automatic quality checks for large projects where many components have to pass repeated tests. OpenCTF is based on the DUnit open source test framework and extends it by specialized test classes and helper functions.

* [DelphiUIAutomation](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/jhc-systems/DelphiUIAutomation). Delphi classes that wrap the MS UIAutomation library. DelphiUIAutomation is a framework for automating rich client applications based on Win32 (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/and specifically tested with Delphi XE5). It is written in Delphi XE5 and it requires no use of scripting languages. It provides a consistent object-oriented API, hiding the complexity of Microsoft's UIAutomation library and windows messages.

## Debugging / error handling ##

* [Delphi LeakCheck](https://bitbucket.org/shadow_cs/delphi-leakcheck/) is a free code library to check the memory leaks in the DUnit and DUnit2 tests. Supports Delphi XE-XE7.

* [FastMM](#memory-managers). Provides powerful memory leak/corruption detection instruments.

* [JclDebug (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/part of Project JEDI)](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/project-jedi/jcl/blob/master/jcl/source/windows/JclDebug.pas). Tracing, MAP file parser, exception report generation, exception stack traces.


## Utilities ##
*Free non-opensource products allowed here.*

## IDE plugins/wizards ##

* [Delphi IDE theme editor / Delphi IDE Colorizer](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/rruz/delphi-ide-theme-editor). Tool to change the IDE color highlighting of several Object Pascal IDE's like Delphi (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/RAD Studio), Appmethod, Lazarus  and Smart Mobile Studio. DITE supports Delphi 5-7, 2005-2010, XE-XE8, Appmethod 1.13-1.14, Lazarus v1.0.1.3 and Smart Mobile Studio IDE v1.1.2.17. The Delphi IDE Colorizer (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/DIC) is a plugin which allows to customize the look and feel of the workspace of the RAD Studio IDE and Appmethod.

* [DDevExtensions](http://andy.jgknet.de/blog/ide-tools/ddevextensions). Extends the Delphi/C++Builder IDE by adding some new productivity features
// *Many useful IDE tweaks, must have.*

* [VCL Fix Pack](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://andy.jgknet.de/blog/bugfix-units/vclfixpack-10). Delphi unit that fixes VCL and RTL bugs at runtime by patching the original functions. If you want all IDE Fix Pack fixes in your application this unit is what you are looking for. Adding the unit to your project (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Delphi and C++Builder) automatically installs the patches that are available for your Delphi/C++Builder version.
// *Actual for Delphi/C++ 6..2009*

* [IDE Fix Pack](http://andy.jgknet.de/blog/ide-tools/ide-fix-pack). Collection of unofficial bug fixes and performance optimizations for the RAD Studio IDE, Win32/Win64 compiler and Win32 debugger. IDE Fix Pack is an IDE plugin for RAD Studio 2009-XE6 that fixes IDE bugs at runtime. All changes are done in memory. No files on disk are modified. None of your projects are modified or benefit from the IDE Fix Pack other than being compiled faster. Only the IDE gets the fixes and optimizations.
// *Supports all RAD Studio versions since 2007. Removes lots of annoying bugs that EMBT haven't fixed for years. Yay!*

* [GExperts](https://sourceforge.net/projects/gexperts). Free set of tools built to increase the productivity of Delphi and C++Builder programmers by adding several features to the IDE. GExperts is developed as Open Source software and we encourage user contributions to the project. Grep search and replace supporting unicode files, DFMs, etc; Automatically rename components, insert text macros, open recent files; Easily backup your projects, with custom additional file lists; Keep nested lists of favorite files for quick access; Track dependencies between units in your project; Quickly jump to any procedure in the current unit; And much, much more...

* [CnWizards](https://github.com/cnpack). Free Plug-in Tool Set for Delphi/C++ Builder/CodeGear RAD Studio to Improve Development Efficiency.

* [Delphi Package Installer (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/DelphiPI)](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://bitbucket.org/idursun/delphipi). Tool which aids you installing components to your Delphi IDE. DelphiPI automatically resolves dependencies between packages, compiles, installs and adds source paths to your IDE.

* [ResEd](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/chaosben/theunknownones). Expert for Delphi 2005, 2006, 2007, 2009, 2010 and XE. This expert is designed for editing the resource files (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/.res; .resx) that are linked to the active project. It will automatically search for all occurrences of {$R xyz.res} lines and will open/create resourcefiles for them. The expert registers itself in the menubar of Delphi under View.

* [Parnassus Bookmarks](https://parnassus.co/delphi-tools/bookmarks). IDE plugin that extends bookmark functionality.
 
* [DelphiSettingManager](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/Arvur/DelphiSettingManager). Multiple IDE profiles for Delphi (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/up to XE6). Allows to install multiple versions of the same component or different component sets for different projects.

* [Delphinus](https://github.com/Memnarch/Delphinus). New Packagemanager which runs on Delphi XE and newer and uses Github as a Backend to Provide the packages.

* [Parnassus Bookmarks](https://parnassus.co/delphi-tools/bookmarks). IDE plugin that extends bookmark functionality.

* [TestInsight](https://bitbucket.org/sglienke/testinsight/wiki/Home). Unit testing IDE Plugin for Delphi. It supports all versions from XE to 10 Seattle. Supports DUnit, DUnit2, DUnitX frameworks.

* [Delphi IDE Explorer](https://github.com/DGH2112/Delphi-IDE-Explorer). Wizard / expert / plugin that allows you to browser the internal fields, methods, properties and events of the IDE.
// *Mainly useful for developers of IDE experts*

* [Multi-RAD Studio IDE Expert Manager](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://www.davidghoyle.co.uk/WordPress/?page_id=1361). Application is for editing the installed experts in all versions of RAD Studio (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/and older Delphi and C++ Builder) on a machine.

* [OTA Interface Search](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/DGH2112/OTA-Interface-Search). Application helps to find Open Tools API (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/OTA) interfaces, methods and properties and understand how to get to those interfaces or methods / properties of the interfaces.

* [AutoSave](https://github.com/DGH2112/Auto-Save). Expert that periodically auto saves all the open modified IDE files.

* [Browse and Doc It](http://www.davidghoyle.co.uk/WordPress/?page_id=872). Plug-in allows you to document and browse your code from within the IDE.

* [Integrated Testing Helper](http://www.davidghoyle.co.uk/WordPress/?page_id=874). Plugin for Delphi and RAD Studio that allows you to run command-line application before and after the compilation of you projects. It also provides the ability to zip you projects files into an archive on each compile/build and manage the application's version information.

* [Project Magician](https://www.uweraabe.de/Blog/2018/05/17/keep-your-project-files-clean-with-project-magician). Wizard for advanced project options manipulation.

* [Selective Debugging](http://www.uweraabe.de/Blog/2015/05/08/selective-debugging/). Wizard that allows to tune for which units their debug version will be used.

* [MMX Code Explorer](https://www.mmx-delphi.de). Feature-rich productivity enhancing plugin. Includes refactoring, class browser, advanced editing, metrict and many more.

* [FormResource](http://chapmanworld.com/2017/03/22/formresource-a-free-delphi-component-for-organizing-product-dependencies). Wizard that helps storing various data as form resources.

* [Delphi Library Helper](https://github.com/littleearth/delphi-library-helper) Tool to assist Delphi developers configuring library folders.

* [Mobile Image Creator](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/littleearth/mobile-image-creator) Creating Icons and Launcher Images for Delphi Mobile Applications (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Firemonkey). This is a fork of Mobile Gfx created by [Thomas Grubb of RiverSoftAVG](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://riversoftavg.com/blogs/index.php/2014/02/03/creating-icons-and-launchers-for-delphi-mobile-applications/).


## Documentation ##

* [SynProject](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/synopse/SynProject) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/[docs](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://synopse.info/fossil/wiki?name=SynProject)). Tool for code source versioning and automated documentation of Delphi projects.

* [PasDoc](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://sourceforge.net/projects/pasdoc). Documentation tool for ObjectPascal (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/FreePascal and Delphi) source code. Documentation is generated from comments found in source code. Available output formats are HTML, HtmlHelp, LaTeX, latex2rtf, simplexml. More output formats may be added in the future.

* [DIPasDoc](http://www.yunqa.de/delphi/products/pasdoc/index). Generates HTML documentation from comments in Pascal source code files. It outputs browsable help as standard HTML files or customizable MS HTML Help projects.


## Code check/review, debug ##

* [GpProfiler2017](https://github.com/ase379/gpprofile2017). Source code instrumenting profiler for Delphi XE and higher. Other forks support older versions.

* [SamplingProfiler](https://www.delphitools.info/samplingprofiler). Performance profiling tool for Delphi 5 to 32bits Delphi XE4. Its purpose is to help locate bottlenecks, even in final, optimized code running at full-speed.

* [Delphi Code Coverage](https://sourceforge.net/projects/delphicodecoverage). Simple Code Coverage tool for Delphi that creates code coverage reports based on detailed MAP files.

* [Pascal Analyzer](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://www.peganza.com/products_pal.html) (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/free Lite version available). Pascal Analyzer, or PAL for short, parses Delphi or Borland Pascal source code. It builds large internal tables of identifiers, and collects other information such as calls between subprograms. When the parsing is completed, extensive reports are produced. These reports contain a great deal of important information about the source code. This information will help you understand your source code better, and assist you in producing code of higher quality and reliability.

* [madExcept](http://madshi.net/madExceptShop.htm). madExcept was built to help you locate bugs in your software. Whenever there's a crash/exception in your program, madExcept will automatically catch it, analyze it, collect lots of useful information, and give the end user the possibility to send you a full bug report. madExcept is also able to find memory leaks, resource leaks and buffer overruns for you.
// **Free **without source** for non-commercial usage (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/only) with some [conditions](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://help.madshi.net/License.htm). Available to download as part of `madCollection` installer (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/you'll need to install `madExcept` item). Pretty well documented.*


## Setup ##

* [Lazy Delphi Builder](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://bitbucket.org/tdelphi/lazy-delphi-builder-downloads). Build tool for Delphi. Recompile projects/packages from sources with all dependencies, without need to mess around with configs. Quickly (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/re-)install components from sources into IDE, with no need to change your Library Path.
// *Powerful automating tool. Freeware but not open source*

* [Inno Setup](http://www.jrsoftware.org/isinfo.php). Free installer for Windows programs. First introduced in 1997, Inno Setup today rivals and even surpasses many commercial installers in feature set and stability.

* [WinSparkle](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://winsparkle.org) and its [Delphi wrapper](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/jkour/neSparkleComponent). WinSparkle is an easy-to-use software update library for Windows developers. WinSparkle is a heavily (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/to the point of being its almost-port) inspired by the Sparkle framework originally by Andy Matuschak that became the de facto standard for software updates on macOS. 

* [Silverpoint MultiInstaller](http://www.silverpointdevelopment.com/multiinstaller/index.htm). Multi component package installer for Embarcadero Delphi and C++Builder, it was created to ease the components installation on the IDE.


## Other ##

* [WMI Delphi Code Creator](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/RRUZ/wmi-delphi-code-creator). Allows you to generate Object Pascal, Oxygene, C++ and C# code to access the WMI (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Windows Management Instrumentation) classes, events and methods. Also includes a set of tools to explorer and Query the content of the WMI.

* [Delphi Preview Handler](https://github.com/RRUZ/delphi-preview-handler). Preview handler for Windows Vista, 7 and 8 which allow you read your object pascal, C++ and Assembly code with Syntax highlighting without open in a editor

* [Delphi Dev. Shell Tools](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/https://github.com/RRUZ/delphi-dev-shell-tools). Windows shell extension with useful tasks for Object Pascal Developers (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/Delphi, Free Pascal).

* [Delphi.gitignore](https://github.com/github/gitignore). .gitignore templates for Delphi. There is also one for Lazarus.

* [OmniPascal](http://omnipascal.com). Project that enables Delphi and Free Pascal developers to write and maintain code using the modern editor [Visual Studio Code](https://code.visualstudio.com).

* [Delphi Unit Tests](https://bitbucket.org/NickHodges/delphi-unit-tests). Set of unit tests for Delphi's libraries. Delphi community members are encouraged to fork the repository, add tests, and create a pull request. Embarcadero employees are particularly encouraged to add tests from the internal tests that are run with official Delphi builds.

* [madDisAsm](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://help.madshi.net/madDisAsm.htm). The package features a full x86 disassembler including MMX, 3dNow enhanced, SSE and SSE2 support. The disassembler can examine a single x86 instruction (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/see ParseCode) or a full function (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/see ParseFunction) and either return a short analysis or a full text disassembly. Register contents are watched/followed if possible, this improves the analyses for jump/call targets. Case/switch jump tables are automatically detected and handled correctly.
// *Free **without source** for non-commercial usage (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/only) with some [conditions](https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/http://help.madshi.net/License.htm). Available to download as part of `madCollection` installer (https://github.com/Fr0sT-Brutal/awesome-delphi/blob/master/you'll need to install `madExcept` item). Pretty well documented.*

* [Chet - C Header Translator for Delphi](https://github.com/neslib/Chet). Chet is a .h-to-.pas translator powered by libclang for Delphi. Uses the Clang compiler to parse header files, resulting in more accurate translations that require fewer manual adjustments.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0)