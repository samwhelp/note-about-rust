

default: help
.PHONY: default




help:
	@echo 'Usage:'
	@echo '	$$ make [action]'
	@echo
	@echo 'Ex:'
	@echo '	$$ make'
	@echo '	$$ make help'
	@echo
	@echo '	$$ make build-book'
	@echo
.PHONY: help




build-book:
	cargo run --package gen-book
.PHONY: build-book




install-just:
	cargo install just
.PHONY: install-just
