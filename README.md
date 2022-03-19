# NGSI-LD Converter 개발
스마트 시티의 다양한 센서 데이터는 NGSI-LD의 포맷에 의해 일관되게 저장된다. 따라서 데이터 통합이 손쉽게 이루어 질 수 있음을 보여준다. 그러나, 

## NGSI-LD Converter 혹은 Database Connecter 개발의 필요성
https://github.com/FIWARE/catalogue/blob/master/core/README.md 에 따르면, Stellio 프로젝트는 Neo4j(https://neo4j.com/) 를 포함하여, TimeScaleDB, PostGIS 데이터베이스에  NGSI-LD 기반 데이터를 저장 및 로드하기 위한 Context Broker를 구축하려고 한다. 하지만, 아직은 Neo4j 등의 데이터베이스와의 연결을 지원하지 않는다. 따라서 NGSI-LD 기반 데이터를 Neo4j에 저장 및 로드할 수 있는 커넥터 및 컨버터를 개발하고자 한다.

## NGSI-LD?
NGSI-LD는 New Generation Service Interface - Linked Data의 약어로서, 상황정보(Context information)에 대해 구독, 질의, 발행하기 위한 정보모델 및 API이고 유럽 표준기관인 ETSI에 의해 제안되었다. NGSI-LD의 목적은 스마트시티와 다른도메인의 데이터를 상호운영/일관되게 교환하기 위해 개발되었다. 데이터모델에 대한 내용은 다음 링크를 참고하시기 바랍니다. https://fiware-datamodels.readthedocs.io/en/stable/howto/index.html 

## NGSI-LD의 특징 및 구조
NGSI-LD는 NGSI-v2의 데이터 모델로부터 관계정보를 확장한 것이 주요한 특징이라고 할수 있다. 

## NGSI-LD Converter의 목적
데이터 모델에 대한 구조 및 내용은 다음 링크에 안내되어 있다.
https://github.com/FIWARE/data-models
