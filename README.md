1. check connectivity to kong
docker run   --network kong_kong-net kong/deck --kong-addr http://kong_kongdbless_1:8001 ping
