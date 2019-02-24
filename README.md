![Swift](https://img.shields.io/badge/Swift-4.2-orange.svg)
![Platform](https://img.shields.io/badge/platform-iOS-lightgrey.svg)
[![License](https://img.shields.io/badge/license-mit-blue.svg)](https://doge.mit-license.org)

# News Reader

Coordinator Pattern + MVVM experiment, with storyboards.

## Description:

The purpose of the project is simply to demonstrate (and learn) how to implement the coordinator pattern in a new iOS project. 

"A Coordinator is an object the encapsulates a lifecycle that is spread over a collection of view controllers. "So what is a coordinator? A coordinator is an object that bosses one or more view controllers around. Taking all of the driving logic out of your view controllers, and moving that stuff one layer up is gonna make your life a lot more awesome" 
-- Soroush Khanlou

### Table of Contents:
- [Why use the Coordinator pattern?](#Why use the Coordinator pattern?)
- [Requirements](#requirements)
- [Contributors](#contributors)
- [Developer](#developer)
- [License](#license)

## Why use the Coordinator pattern?

- Clear navigation
- Separation of concerns
- Smaller View Controllers
- Unchained module-to-module responsibility / Isolation
- Modules completely independent from one another
- Every task and sub-task has a dedicated way of being encapsulated
- Reusable ViewControllers / Modules
- Controllers can be easily integrated into different flows
- Coordinators separate display-binding from side effects
- Simplified testing

## Normally ViewControllers are tasked with:

- Model-View Binding
- Subview Allocation
- Data Fetching
- Layout
- Data Transformation
- Navigation Flow
- User Input
- Model Mutation

## The purpose of the Coordinator:

- Handle the navigation flow

## How do ViewControllers communicate with the Coordinator:

- Delegate Pattern
- Callbacks

## What is Module?

A module is one architectural element of MVC, MVP, MVVM, and Viper architecture approaches. In the simplest case, for MVC, module is a controller and, for Viper, an Interactor-Presenter-View.

## Architecture

App uses a similar concept of MVVM + Coordinators pattern:

- Coordinator instantiates view controllers, injects dependencies

## Inspired by:

Soroush Khanlou - [Migrating To Coordinators](http://khanlou.com/2017/04/migrating-to-coordinators/)

### Requirements:

* iOS 11.3+ / Mac OS X 10.11+ / tvOS 9.0+
* Xcode 10.1
* Swift 4.2
* iPhone with A9 processor or later

### Developer:

Clint Mejia - [clint_m@clintmejia.com](clint_m@clintmejia.com)


### License:

This project is licensed under the terms of the [MIT license](https://opensource.org/licenses/MIT).
