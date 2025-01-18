This README provides guidance for working with the fonts used in this project and handling specific formatting considerations.

Fonts

1. Source Sans Pro

Source Sans Pro is a clean, modern sans-serif font, ideal for user interfaces and general text readability. If your computer does not already have this font installed, you can download it from:

Official Website: https://fonts.google.com/specimen/Source+Sans+Pro

GitHub Repository: https://github.com/adobe-fonts/source-sans-pro

2. Spin Cycle OT

Spin Cycle OT is a decorative font often used for playful or artistic designs. Since this is not a standard system font, you may need to download and install it separately. It is available at:

Official Source: [Provide a specific link or source if applicable]

Alternative Sources: Font libraries or digital asset marketplaces

To install these fonts:

Download the font files (.ttf or .otf format).

Double-click the file and select "Install" on Windows or "Install Font" on macOS.

Formatting Considerations

Handling Float Values

Some values in this project are represented as floating-point numbers. To improve readability, you can round these values. Use the following guidelines for rounding:

For general display: Round to 2 decimal places (e.g., 3.14159 becomes 3.14).

For financial or percentage data: Round to the nearest whole number or use domain-specific precision requirements.

Examples:

# Python example for rounding
value = 3.14159
rounded_value = round(value, 2)  # 3.14

Styling with Fonts

When designing documents, presentations, or user interfaces with these fonts:

Use Source Sans Pro for body text and functional components.

Reserve Spin Cycle OT for headings, logos, or decorative elements.

Ensure consistency in typography by sticking to these font roles unless the design explicitly requires deviation.

Troubleshooting

Font Not Displaying Correctly: Verify the font is installed and active on your operating system.

Compatibility Issues: Some older software may not support custom fonts. Consider converting text to outlines in graphic software or using system-supported alternatives.

For further assistance, feel free to reach out to the project team.