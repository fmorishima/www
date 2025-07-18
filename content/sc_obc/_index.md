+++
+++

{% section_title(bg="", title="SC-OBC MODULE A1", subtitle="", slogan="", style_top="製品情報/SC-OBC Module A1") %}
<!--display element -->
{% end %}

{% quick_jump(
	title1="Product overview", id1="section-summary",
	title2="Use cases", id2="section-usage",
	title3="Dev kit", id3="section-devkit",
	title4="Specifications", id4="section-specs",
	title5="Docs / resources", id5="section-docs"
) %}
<!--display element -->
{% end %}

<section id="section-summary">
	{% hero_element(
		title="PRODUCT",
		img="sc-obc_module_a1.png",
		alt="",
		link="",
		link_text="",
		img_link="",
		bg="",
		subtitle="",
		slogan=""
	) %}
	JAXAが国際宇宙ステーションで培った信頼性設計技術を基にキューブサット用に最適設計した宇宙用コンピュータです。Xilinx製 Artix-7 FPGAを採用し、インターフェースの種類や数をユーザ毎に柔軟に対応することができます。キューブサット以外の宇宙機や地上の産業用途にも使用可能です。
	{% end %}

<section id="section-usage">
	{% section_title(bg="", title="USES", subtitle="", slogan="") %}
	<!--display element -->
	{% end %}
</section>

{% twocard(
	title="",
	subtitle="",

	left_card_image="interface.jpg",
	right_card_image="satellite.jpg",

	left_card_title="",
	left_card_subtitle="弊社人工衛星に搭載するため、<br> <br> PC104形状に合わせたインタフェースボードの上にSC-OBC Module A1を搭載した形態。",

	right_card_title="",
	right_card_subtitle="インタフェースボードに 搭載したSC-OBC Module A1が 組み込まれた人工衛星。<br> <br> （写真は開発中のもの）",

	bg=""
) %}
<!--display element -->
{% end %}

<section id="section-devkit">
	{% section_title(bg="", title="DEV KIT", subtitle="", slogan="") %}
	<!--display element -->
	{% end %}
</section>

{% twocard(
	title="",
	subtitle="",
	left_card_image="under_construction.jpeg",
	right_card_image="under_construction.jpeg",
	left_card_title="開発セット",
	left_card_subtitle="coming soon",
	right_card_title="オプション製品",
	right_card_subtitle="coming soon",
	bg=""
) %}
<!--display element -->
{% end %}

<section id="section-specs">
	{% spec_sheet(
		bg="",
		title="SPECS",
		subtitle="",
		slogan=""
	) %}
	Main Processor | Xilinx Artix-7
	Communication Interface | CAN, I2C, UART
	Main CPU | Cortex-M3 / MicroBlaze-V
	FPGA User I/O | 38 pin
	Preinstalled OS | Zephyr RTOS
	PIC User I/O | 3 pin
	Clock Generator | 24 MHz x 2
	Watchdog timer | 1 (IP Core)
	PIC (anomaly detection / system recovery) | 8 bit PIC MCU
	Interface Connector | 80 pin / 0.5 mm pitch
	On-chip SRAM | 64 KByte FPGA Block RAM
	Supply Voltage | DC 5.0 V ± 10%
	On-board SRAM | 4 MBytes
	Power Consumption | 2.0 W (Max)
	NOR Flash Memory (configurable) | 32 MBytes x 2
	External Dimensions | 70 x 70 x 9.6 mm
	FeRAM | 512 KBytes x 2
	Mass | 130 g
	{% end %}
</section>

<section id="section-docs">
	{% docs_resources(
		bg="",
		title="DOCS",
		subtitle="",
		slogan=""
	) %}
	ユーザーマニュアル | SC-OBC Module A1の仕様、通信系統、回路構成等について記載されています。 | https://github.com/spacecubics/scobc-a1-product-manual/tree/main
	FPGA ハードウェアマニュアル | SC-OBC Module A1に搭載されているFPGAの仕様書です。FPGAの開発や、ソフトウェアの開発に必要な、FPGA機能に関する仕様やレジスタの仕様が記載されています。 | https://docs.zephyrproject.org/latest/boards/sc/scobc_a1/doc/index.html
	GitHub | その他、様々な技術情報はこちらを参照ください。 | https://github.com/spacecubics
	{% end %}
</section>

{% prefooter(
	left_card_image="earth.jpg",
	right_card_image="ir.jpg",

 left_title="RECRUIT",
	left_subtitle="採用情報",
	left_footer_1="一緒に働く仲間を常に募集しています。",
	left_footer_2="ご興味のある方はご連絡ください。",
	left_link="/recruit",

	right_title="IR INFO",
	right_subtitle="投資家情報",
	right_footer_1="ステークホルダーの皆様に向けて",
	right_footer_2="決算や適時開示情報などをご紹介しています。",
	right_link="/ir_info",

	bottom_card_image = "",
	bottom_title = "CONTACT",
	bottom_subtitle = "お問い合わせ",
	bottom_footer_1 = "事業やサービスについてご相談・ご質問承ります。",
	bottom_footer_2 = "お気軽にお問い合わせください。",
	bottom_link = "/contact",

	bg=""
) %}
<!--display element -->
{% end %}
