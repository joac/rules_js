# Debugging life cycle hooks

Go to lifecycle folder:
```sh
cd npm/private/lifecycle
```

Install npm dependencies
```sh
npm i
```

Go back to repo root:
```sh
cd -
```

Add the override file

```sh
OVERRIDE="--override_repository=aspect_rules_js=$(pwd)" echo "common:override $OVERRIDE" >> ~/.bazelrc
```

