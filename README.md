# repos

## spec-v1

zeroserver rationale:
- cloud alternative
- provide python/pyodide environment that uses libp2p mesh like Kazaa disruption to cloud
- lots of business opportunity from cost reduction, security delta, devops changes, 
- lots of societal potential due to society changes, economics of data, freedom of thought, AI, LLM, etc. 

## zs-state

this is the state holding/management abstraction for zeroserver

- pubsub
- block/blob
- sqlmodel|sqlite ORM synchronization

## zs-datamesh

this is the peer-to-peer system, which provides synchronization of zs-state over libp2p and other Pyodide setups 

- initial testing implementation: dummy/mockup
- Pyro5 over TCP for Shiny
- Pyro5 over Websockets for Shinylive
- Pyro5 over Pyodide proxy / libp2p

## nowkast

this is an example app that uses this framework, a set of social media widgets
- built on Shiny, uses zeroserver

Prototype 0.0.1
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
- auth middleware

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

80% complete, ETA Dec 1

## WP2: add automated chatbot functions through langchain

## WP3: create hivemind/petals powered custom LLM interface

## WP4: power WP3 by CTIO incentivation system
