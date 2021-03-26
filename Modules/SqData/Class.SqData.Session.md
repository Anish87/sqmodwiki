# Description

A session is (like) a connection handler to databases.

----

## Alias

* `class` SqData.Session

## Meta-methods

* `function` \_typename

## Constructors

* `constructor` [SqData.Session](Constructor.SqData.Session)

## Member Properties

* `bool` [IsConnected](Property.SqData.Session.IsConnected)
* `bool` [IsGood](Property.SqData.Session.IsGood)
* `integer` [LoginTimeout](Property.SqData.Session.LoginTimeout)
* `integer` [ConnectionTimeout](Property.SqData.Session.ConnectionTimeout)
* `bool` [CanTransact](Property.SqData.Session.CanTransact)
* `bool` [IsTransaction](Property.SqData.Session.IsTransaction)
* `string` [Connector](Property.SqData.Session.Connector)
* `string` [URI](Property.SqData.Session.URI)

## Member Methods

* `function` [Open](Function.SqData.Session.Open)
* `function` [Close](Function.SqData.Session.Close)
* `function` [Reconnect](Function.SqData.Session.Reconnect)
* `function` [Statement](Function.SqData.Session.Statement)
* `function` [RecordSet](Function.SqData.Session.RecordSet)
* `function` [Begin](Function.SqData.Session.Begin)
* `function` [Commit](Function.SqData.Session.Commit)
* `function` [Rollback](Function.SqData.Session.Rollback)
* `function` [HasTransactionIsolation](Function.SqData.Session.HasTransactionIsolation)
* `function` [IsTransactionIsolation](Function.SqData.Session.IsTransactionIsolation)
* `function` [SetFeature](Function.SqData.Session.SetFeature)
* `function` [GetFeature](Function.SqData.Session.GetFeature)
* `function` [SetProperty](Function.SqData.Session.SetProperty)
* `function` [GetProperty](Function.SqData.Session.GetProperty)
* `function` [Execute](Function.SqData.Session.Execute)
* `function` [ExecuteAsync](Function.SqData.Session.ExecuteAsync)

## Static Properties

* `integer` [LoginTimeoutDefault](Property.SqData.Session.LoginTimeoutDefault)
* `integer` [TransactionReadUncommitted](Property.SqData.Session.TransactionReadUncommitted)
* `integer` [TransactionReadCommitted](Property.SqData.Session.TransactionReadCommitted)
* `integer` [TransactionRepeatableRead](Property.SqData.Session.TransactionRepeatableRead)
* `integer` [TransactionSerializable](Property.SqData.Session.TransactionSerializable)

## Static Methods

* `function` [GetURI](Function.SqData.Session.GetURI)