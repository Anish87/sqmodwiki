# Description

Fast, efficient and flexible implementation of the [signals and slots](https://en.wikipedia.org/wiki/Signals_and_slots) concept. Used heavily throughout the plug-in to deliver events from the server as well as the plug-in itself. Some features or safeguards have been omitted for the sake of efficiency. However, the implementation is solid enough to deliver a good experience when dealing with events.

----

## Aliases:

* `class` SqSignalBase

## Meta-methods

* `function` [\_typename](Function.SqSignalBase._typename)
* `function` [\_tostring](Function.SqSignalBase._tostring)

## Properties

* `object` [Data](Property.SqSignalBase.Data)
* `string` [Name](Property.SqSignalBase.Name)
* `integer` [Slots](Property.SqSignalBase.Slots)
* `bool` [Empty](Property.SqSignalBase.Empty)

## Methods

* `function` [Connect](Function.SqSignalBase.Connect)
* `function` [ConnectOnce](Function.SqSignalBase.ConnectOnce)
* `function` [Exists](Function.SqSignalBase.Exists)
* `function` [Disconnect](Function.SqSignalBase.Disconnect)
* `function` [ExistsThis](Function.SqSignalBase.ExistsThis)
* `function` [ExistsFunc](Function.SqSignalBase.ExistsFunc)
* `function` [Count](Function.SqSignalBase.Count)
* `function` [CountThis](Function.SqSignalBase.CountThis)
* `function` [CountFunc](Function.SqSignalBase.CountFunc)
* `function` [Lead](Function.SqSignalBase.Lead)
* `function` [LeadThis](Function.SqSignalBase.LeadThis)
* `function` [LeadFunc](Function.SqSignalBase.LeadFunc)
* `function` [Tail](Function.SqSignalBase.Tail)
* `function` [TailThis](Function.SqSignalBase.TailThis)
* `function` [TailFunc](Function.SqSignalBase.TailFunc)
* `function` [Eliminate](Function.SqSignalBase.Eliminate)
* `function` [EliminateThis](Function.SqSignalBase.EliminateThis)
* `function` [EliminateFunc](Function.SqSignalBase.EliminateFunc)
* `function` [Emit](Function.SqSignalBase.Emit)
* `function` [Query](Function.SqSignalBase.Query)
* `function` [Consume](Function.SqSignalBase.Consume)
* `function` [Approve](Function.SqSignalBase.Approve)
* `function` [Request](Function.SqSignalBase.Request)
