# actions-slack-notify
Send slack notifications with easy

# Usage
Example:
```yaml
      - name: notify team
        uses: transferwise/actions-slack-notify@v1
        with:
          channel: "#events"
          text: |
            *[notification]* 
            This is to notify you about notification
            :github:
          token: ${{ secrets.SLACK_API_TOKEN }}
```