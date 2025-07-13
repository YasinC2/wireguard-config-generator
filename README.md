# WireGuard Config Generator
A web-based tool for generating WireGuard VPN configuration files and shareable links with custom settings.

## Features

- Generate multiple WireGuard configurations from endpoint lists
- Load pre-configured IP endpoints from external sources
- Import/export configuration settings via file or WireGuard link
- Manage private keys with local storage support
- Custom advanced settings (DNS, MTU, AllowedIPs, etc.)
- Bulk copy/download generated configurations
- Responsive UI with Tailwind CSS

## What This Tool Does

This tool simplifies creating WireGuard VPN configurations by providing:
1. **Endpoint Management**: Load endpoints from text/JSON sources or manual input
2. **Key Handling**: Store/load private keys with browser storage and pre-loaded options
3. **Configuration Generation**: 
   - Automatic config file creation
   - Shareable WireGuard links
   - Bulk export capabilities
4. **Customization**: Adjust advanced networking parameters through an intuitive UI

## Basic Workflow

1. Input endpoints manually or load from provided sources
2. Enter/select private key
3. (Optional) Enable advanced settings
4. Click "Generate Configs"
5. Copy links or download configurations

## Credits

Third-party resources used:
- [Tailwind CSS](https://tailwindcss.com) - MIT License
- [JSZip](https://stuk.github.io/jszip/) - MIT License
- [FileSaver.js](https://github.com/eligrey/FileSaver.js) - MIT License
- Endpoint sources:
  - [darknessm427/IP_Generator](https://github.com/darknessm427/IP_Generator)
  - [ircfspace/endpoint](https://github.com/ircfspace/endpoint)
- Pre-loaded keys from [YasinC2/wg-config-fetcher](https://github.com/YasinC2/wg-config-fetcher)

## License

MIT License - See [LICENSE](LICENSE) file
