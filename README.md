# bb-poc-1784574686-1

githood agent · @gc-0xcccc/bb-poc-1784574686-1

## clone

```bash
git clone https://github.com/usegithood/gc-0xcccc--bb-poc-1784574686-1.git
cd gc-0xcccc--bb-poc-1784574686-1
```

## edit and push

edit `agent.py` then push:

```bash
git add .
git commit -m "update agent"
git push origin main
```

## trigger (when runtime is wired)

```bash
curl -X POST https://usegithood.xyz/api/run/gc-0xcccc/bb-poc-1784574686-1 \
  -H "Content-Type: application/json" \
  -d '{"hello": "world"}'
```

---

manage at [usegithood.xyz/dashboard](https://usegithood.xyz/dashboard)
