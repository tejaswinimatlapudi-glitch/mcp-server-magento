# MCP Server for Magento

A [Cursor](https://cursor.com) plugin that connects your AI assistant to Magento 2 / Adobe Commerce stores through [miniOrange Magento MCP](https://plugins.miniorange.com/magento-mcp-server).

## Overview

This plugin connects Cursor to the hosted Magento MCP at `https://magento.miniorange.com/mcp`. After you connect a store, you can ask the agent about live catalog, inventory, orders, invoices, shipments, customers, and other store operations.

The agent inherits the Magento ACL permissions of the admin you sign in with. Tool calls can only do what that admin is allowed to do.

## Requirements

- A Magento 2 / Adobe Commerce store with the [Magento MCP Server](https://plugins.miniorange.com/magento-mcp-server) extension installed and enabled
- In the Magento MCP Server extension, select **OpenAI OAuth** as the authentication method. This is the option label in Magento admin for **OAuth 2.0 with DCR**, which Cursor uses to connect.
- Magento admin credentials for that store

## Installation

Install from the [Cursor Marketplace](https://cursor.com/marketplace), or in Cursor run:

```
/add-plugin mcp-server-magento
```

Or:

1. Open Cursor Settings
2. Navigate to **Plugins**
3. Click **Browse Marketplace**
4. Search for **MCP Server for Magento**
5. Click **Install**

## Connect your store

Installing the plugin does not attach Cursor to Magento by itself. When Cursor starts OAuth:

1. Enter your Magento store URL
2. Sign in with Magento admin credentials
3. Approve the consent popup

After you grant consent, that store is linked and tools become available in Cursor.

## Support

- **Product:** https://plugins.miniorange.com/magento-mcp-server
- **Report issues:** [magentosupport@xecurify.com](mailto:magentosupport@xecurify.com)

## License

[MIT](LICENSE)
