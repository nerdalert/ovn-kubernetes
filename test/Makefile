.PHONY: install-kind
install-kind:
	./scripts/install-kind.sh

.PHONY: install-cno-kind
install-cno-kind:
	./scripts/install-cno-kind.sh

.PHONY: shard-%
shard-%:
	./scripts/e2e-kind.sh $@ $(WHAT) 

.PHONY: control-plane
control-plane:
	./scripts/e2e-cp.sh
