## Overview

This Jackson extension adds XML reading/writing support for JAX-RS implementations like [Jersey](http://jersey.java.net/) and [RESTeasy](http://www.jboss.org/resteasy).
This is done by class `JacksonJsonProvider` implementing `javax.ws.rs.ext.MessageBodyReader` and `javax.ws.rs.ext.MessageBodyWriter` that JAX-RS defines for pluggable support for data formats. 
`JacksonXMLProvider` (and `JacksonJaxbXMLProvider`) can then be registered with JAX-RS container to make Jackson the standard XML reader/writer provider.

## Status

Module is fully usable. It depends on Jackson 2.0 API.

## Maven dependency

To use this extension on Maven-based projects, use following dependency:

    <dependency>
      <groupId>com.fasterxml.jackson.jaxrs</groupId>
      <artifactId>jackson-jaxrs-xml-provider</artifactId>
      <version>2.0.0-SNAPSHOT</version>
    </dependency>

(or whatever version is most up-to-date at the moment)

## Usage

(to be written)
