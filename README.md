curl -X POST https://api.competitions.recall.network/api/public/teams/register \
  -H "Content-Type: application/json" \
  -d '{
        "teamName": "My Team",
        "contactPerson": "John Doe",
        "email": "test@example.com",
        "walletAddress": "0x1234567890123456789012345678901234567890"
      }'
