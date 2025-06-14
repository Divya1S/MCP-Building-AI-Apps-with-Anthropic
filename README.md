<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MCP: Build Rich-Context AI Applications with Anthropic</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100 font-sans">
    <div class="container mx-auto px-4 py-8">
        <header class="text-center mb-8">
            <h1 class="text-4xl font-bold text-gray-800">MCP: Build Rich-Context AI Applications with Anthropic</h1>
            <p class="text-lg text-gray-600 mt-2">A project demonstrating the Model Context Protocol (MCP) for integrating rich context into AI applications.</p>
        </header>

        <section class="bg-white shadow-md rounded-lg p-6 mb-8">
            <p class="text-gray-700">This project demonstrates how to implement the <strong>Model Context Protocol (MCP)</strong>, an open protocol developed by Anthropic to standardize how Large Language Models (LLMs) access tools, data, and prompts from external sources. MCP simplifies integrating rich context into AI applications by defining a client-server architecture for communication between an MCP client (hosted in the AI app) and an MCP server (exposing tools, resources, and prompt templates). The server can run locally as a subprocess or remotely as an independent process.</p>
        </section>

        <section class="mb-8">
            <h2 class="text-2xl font-semibold text-gray-800 mb-4">Features</h2>
            <ul class="list-disc list-inside text-gray-700 space-y-2">
                <li><strong>Standardized Integration</strong>: Connect AI applications to external data sources and tools with minimal custom integration.</li>
                <li><strong>Client-Server Architecture</strong>: Learn how MCP clients and servers communicate to provide LLMs with dynamic context.</li>
                <li><strong>Chatbot Implementation</strong>: Build an MCP-compatible chatbot with custom tools, such as searching academic papers.</li>
                <li><strong>Local MCP Server</strong>: Create and test a local MCP server using FastMCP, exposing tools, resources, and prompt templates.</li>
                <li><strong>MCP Client</strong>: Integrate an MCP client into a chatbot to connect dynamically to MCP servers.</li>
                <li><strong>Reference Servers</strong>: Connect to Anthropic’s reference servers like <code>filesystem</code> (for filesystem operations) and <code>fetch</code> (for web content extraction as markdown).</li>
                <li><strong>Claude Desktop Integration</strong>: Configure Claude Desktop to connect to your MCP server and other open-source servers, abstracting low-level MCP client logic.</li>
                <li><strong>Remote Deployment</strong>: Deploy an MCP server remotely and test it with MCP Inspector or other MCP-compatible applications.</li>
                <li><strong>Future Roadmap</strong>: Explore upcoming MCP features, including multi-agent architecture, MCP registry API, server discovery, authorization, and authentication.</li>
            </ul>
        </section>

        <section class="mb-8">
            <h2 class="text-2xl font-semibold text-gray-800 mb-4">Prerequisites</h2>
            <ul class="list-disc list-inside text-gray-700 space-y-2">
                <li><strong>Python 3.8+</strong> (for FastMCP and MCP-compatible tools)</li>
                <li><strong>Node.js</strong> (optional, for certain MCP server implementations)</li>
                <li><strong>FastMCP</strong> for building and testing MCP servers</li>
                <li><strong>MCP Inspector</strong> for testing MCP server functionality</li>
            </ul>
        </section>

    </div>
</body>
</html>
