
# SixHour-CloudPC

A Windows cloud PC controlled using GitHub Actions.

## Features

- Windows 11 virtual machine
- Remote Desktop connectivity
- Automated startup
- Approximately six-hour sessions
- Automatic VM deallocation
- Manual shutdown workflow

## Requirements

- GitHub account
- Eligible Azure subscription
- Windows 11 development/testing VM
- Azure authentication through GitHub OIDC

## Usage

1. Configure Azure credentials and permissions.
2. Add the required GitHub secrets and variables.
3. Open the Actions tab.
4. Select Start Six-Hour Cloud PC.
5. Click Run workflow.
6. Connect to your VM using Remote Desktop.

The VM is automatically deallocated
after approximately six hours.

## Security

Never commit passwords, private keys,
or cloud credentials.

Never expose RDP to the entire internet.
Restrict access to trusted network addresses.

## License

MIT
