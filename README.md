# memcached-operator

make docker-build IMG=qteqno/memcached-operator:v0.0.1

 make docker-push IMG=qteqno/memcached-operator:v0.0.1

 cd config/default 

 kustomize edit set namespace mynamespace 

 make deploy IMG=qteqno/memcached-operator:v0.0.1