awk 'NF >= 2 {
  path = $2
  sub(/^\.\//, "", path)
  print path
}' "$CHECKSUM_FILE"

# Unibit-Stock-API-Examples
A Jupyter notebook to show various uses of UniBit Stock API
