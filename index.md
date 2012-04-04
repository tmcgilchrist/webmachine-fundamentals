## Prelude

## Table Of Contents

* ####[Introduction](#introduction)
* ####[Fundamentals](#fundamentals)
    * [REST & HTTP](#rest-http)
* ####[The Basics](#thebasics)
    * [Overview](#overview)
    * [Dispatch](#dispatch)
    * [Resources](#resources)
    * [Authentication](#authentication)
* ####[RESTful Applications](#restfulapps)
    * [Building RESTful applications with Backbone](#restful-backbone)
* ####[Advanced](#advanced)
    * [Debugging](#debugging)
    * [Caching](#caching)
    * [Testing](#testing)
* ####[Resources](#other-resources)

# <a name="introduction">Introduction</a>

Erlang as a language for developing web applications. Probably not the natural
choice for many people but it can be very productive and brings a number of
unique advantages.

What is Erlang?

Go through and define some basic details about Erlang and what makes it special
and interesting.

Point readers to the Learn You Some Erlang website.

## <a name="fundamentals">Fundamentals</a>

### <a name="rest-http">REST & HTTP</a>

## REST

## HTTP

## <a name="thebasics">The Basics</a>

### What is WebMachine?

Webmachine is often called a REST toolkit, rather than a web framework. And I'd
tend to agree. Being a Ruby/Rails programmer for much of my time I draw
parallels between WebMachine and the Sinatra project in Ruby land. Both take a
stance on including the kitchen sink, and allow you the developer a huge amount
of scope in the areas that they don't have an opinion.

WebMachine provides a layer on top of HTTP, providing you with a correctly
implemented HTTP state machine in which you inject your pieces of logic. It
handles working out the low level details of content negotiation, HTTP Status
codes and all that other low level detail. You provide it with a set of
resources as Erlang modules, implementing specific methods and WebMachine takes
it from there.

### Why should you consider using it?

WebMachine is a great tool for exposing Resources as a REST API, and if that's
what you want to do then it'll be a good fit. If instead you're looking for a
fully featured Web Development framework, ala Rails or Django, then something
like ChicagoBoss is likely more your style.

WebMachine doesn't have an opinion on how to talk to a DB or interface with
other pieces of your system, it provides a REST/HTTP toolkit, a damn good one,
but that's pretty much it.

## 5 Minute Webmachine

#### Generate a new project using rebar

Modify supervisor to startup webmachine.

Load the dispatch.conf file.

## The Basics

### <a name="dispatch">Dispatch</a>

Present the options you have for defining the url routes.
 * provide a config file like dispatch.conf
 * define them in app.config
 * define them in each resource but appending to the routes data structure.

### <a name="resources">Resources</a>

We want to define how to handle the common use cases
 GET resource
 PUT resource
 POST resource

Fancy options? support for PATCH etc

### <a name="authentication">Authentication</a>

## <a name="restfulapps">RESTful Applications</a>

### <a name="restful-backbone">Building RESTful applications with Backbone</a>

## <a name="advanced">Advanced</a>

### <a name="debugging">Debugging</a>
### <a name="caching">Caching</a>
### <a name="testing"></a>

## <a name="other-resources">Resources</a>
