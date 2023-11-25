# repos

## spec-v1



## zs-state

this is the state holding/management abstraction for zeroserver

- pubsub
- block/blob
- sqlmodel ORM session

## zs-datamesh

this is the peer-to-peer system, which provides synchronization of zs-state over libp2p and other Pyodide setups 

## nowkast

this is an example app that uses this framework

- defines sqlmodel 
- uses zs-state to get a session




# python use

- 3.11+
- typing
- dataclasses, extensions from SqlModel
- metaclasses?



# stack

## starlette / uvicorn / fastapi

- Route and Mount, of apps+endpoints

## shiny

R versus python

## htmltools

## sqlmodel

- pydantic
- sqlalchemy

## Pydantic / FastAPI 

- allows REST wrappers around the same calls/methods used by Shiny.server

## pandas, seaborn

## shinylive

## poetry




# plan

## WP1: build basic nowkast demo and embed in zeroserver partners' websites

### still TBD

- auth system?

## WP2: add automated chatbot functions through langchain

## WP3: create hivemind/petals powered custom LLM interface

## WP4: power WP3 by CTIO incentivation system
