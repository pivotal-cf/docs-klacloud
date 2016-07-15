---
title: ISS Knowtify Search Analytics for Pivotal Cloud Foundry&reg;
owner: London Services
---

This documentation describes the ISS Knowtify Search Analytics (KSA) tile for Pivotal Cloud Foundry&reg; (PCF).

<p class="note"><strong>Note</strong>: This product was previously known as Knowtify Log Analytics for Pivotal Cloud Foundry&reg;.</p>

##<a id='overview'></a> Overview

Knowtify Search Analytics (KSA) integrates log analytics and search, log ingestion and visualization in one platform.  Easy to deploy due to its integration with Pivotal Cloud Foundry, KSA is based on Apache Solr ®️, the highly scalable open source search project.  Cloud Foundry users are given near-real-time actionable knowledge with customizable analytic displays to support rapid decision-making. 

The features of KSA include:

* KSA is fully integrated with Pivotal Cloud Foundry & Cloud Foundry Loggregator
* KSA was designed to be dynamically scalable to 50 nodes of Solr and hundreds of millions of documents
* Monitor log data to track activity and quickly search and display custom dashboards to monetize insight
* Visualize data from multiple data sources in one application
* Detect and solve security-related events faster

##<a id='snapshot'></a> Product Snapshot

<dl>
<dt>Current ISS Knowtify Search Analytics Tile for Pivotal Cloud Foundry Details</dt>
<dd><strong>Version</strong>: v1.0.1.1 </dd>
<dd><strong>Release date</strong>: July 15, 2016</dd>
<dd><strong>Software component version</strong>: Knowtify Search Analytics v1.0.1.1</dd>
<dd><strong>Compatible Ops Manager version(s)</strong>: 1.5.x, 1.6.x, 1.7.x</dd>
<dd><strong>Compatible Elastic Runtime version(s)</strong>: 1.4.x, 1.5.x, 1.6.x, 1.7.x</dd>
<dd><strong>vSphere support?</strong> </dd>
<dd><strong>AWS support?</strong> </dd>
<dd><strong>OpenStack support?</strong>  </dd>
</dl>

##<a id='feedback'></a> Feedback

Please provide any bugs, feature requests, or questions to the [Pivotal Cloud Foundry Feedback](mailto:pivotal-cf-feedback@pivotal.io) list or to [ISS](mailto:knowtify@issinc.com).

## Upgrading to the Latest Version

Starting with beta version 0.1.1 an upgrade path will be provided  to upgrade from version 0.1.1 to future versions.

<p class="note"><strong>Note</strong>: Uninstalling previous versions of this tile will delete all data and saved dashboard settings.</p>

## Installation Steps Using Pivotal Ops Manager and User Documentation Provided at:

   http://www.issinc.com/wp-content/uploads/KLA_Pivotal.pdf

Overview
This topic will be the landing page for the repo. It should follow the following format:

Overview

Knowtify Search Analytics provides a scalable search engine install along with a powerful, server-based, dashboard that allows the viewing of timebased or non-timbased information.  

Key Features

Search Engine Install (Scalable)
Dashboard for search
Easy Log Viewing for Pivotal Cloud Foundry

Partner Service Broker

A Service Broker allows Cloud Foundry applications to bind to services and consume the services easily from App Manager UI or command line. The Partner Service Broker will enable you to use one or more Partner accounts and is deployed as a Java Application on Cloud Foundry. The Broker exposes the Partner service on the Cloud Foundry Marketplace and allows users to directly create a service instance and bind it to their applications either from the Pivotal Apps Manager Console or from the command line. 

The PCF (Pivotal Cloud Foundry) Tile for Partner installs the Partner Service Broker as an application and registers it as a Service Broker on Cloud Foundry and exposes its service plans on the Marketplace.  This makes the installation and subsequent use of Partner on your Cloud Foundry applications simple and easy. 

If trial license available => Customers interested in using Partner can obtain a 60 day free trial license from edit link here.

Product Snapshot

Current ISS Knowtify Search Analytics Tile for Pivotal Cloud Foundry Details
Version: 1.0.1.1
Release Date: July 15, 2016
Software components versions: Knowtify Search Analytics 1.0.1.1
Compatible Ops Manager Version(s): 1.5.x, 1.6.x, 1.7.x
Compatible Elastic Runtime Version(s): 1.4.x, 1.5.x, 1.6.x, 1.7.x

Requirements (or Prerequisites, Packaging Dependencies for Offline Buildpacks, 
etc.)

I don’t believe we have any prerequisites so long as Ops Manager and Elastic Runtime versions are within scope.

Feedback

Please provide any bugs, feature requests, or questions to the Pivotal Cloud Foundry Feedback list.