<p align="right">
    <a href="https://badge.fury.io/bo/veams-component-rte"><img src="https://badge.fury.io/bo/veams-component-rte.svg" alt="Bower version" height="20"></a>
    <a href="https://gitter.im/Sebastian-Fitzner/Veams?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge"><img src="https://badges.gitter.im/Sebastian-Fitzner/Veams.svg" alt="Gitter Chat" /></a>
</p>


# Rich Text Editor (Markdown Component)

## Description

The RTE component is a simple partial which supports the usage of markdown files just by refencing them in your file system. 
You need to make sure that you start the link to your file at the root directory.

-----------

## Requirements

- [mangony-hbs-helpers]() - _In this library a markdown parser is integrated._

-----------

## Installation 

### Installation with Veams

`veams install vc rte`

### Installation with Bower

`bower install veams-component-rte --save`

----------- 

## Fields

#### Settings

- settings.rteContextClass {`String`} [default] - _Context class of the rte._
- settings.rteClasses {`String`} - _Modifier classes for the rte._

#### Content 

- content.rteMd {`String`} - _Path to markdown file (starting at the root directory)._
- content.rtes {`Array`} - _You can pass an array to this component which consists of multiple rteMd references._
- content.rtes.rteMd {`String`} - _Path to markdown file (starting at the root directory)._