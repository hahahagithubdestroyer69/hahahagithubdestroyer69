-- Gui to Lua
-- Version: 3.2

-- Instances:

local Scatsus = Instance.new("ScreenGui")
local TextButton = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local INFO = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local ImageLabel = Instance.new("ImageLabel")
local UICorner_3 = Instance.new("UICorner")
local Frame_2 = Instance.new("Frame")
local UICorner_4 = Instance.new("UICorner")
local ImageLabel_2 = Instance.new("ImageLabel")
local TextLabel_3 = Instance.new("TextLabel")
local UICorner_5 = Instance.new("UICorner")
local TextLabel_4 = Instance.new("TextLabel")
local UICorner_6 = Instance.new("UICorner")
local EXECUTOR = Instance.new("Frame")
local UICorner_7 = Instance.new("UICorner")
local TextBox = Instance.new("TextBox")
local UICorner_8 = Instance.new("UICorner")
local TextButton_2 = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local TextButton_3 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local TextButton_4 = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local TextButton_5 = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local TextButton_6 = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local Scripthub = Instance.new("Frame")
local UICorner_14 = Instance.new("UICorner")
local ScrollingFrame = Instance.new("ScrollingFrame")
local UIGridLayout = Instance.new("UIGridLayout")
local TextButton_7 = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local TextButton_8 = Instance.new("TextButton")
local UICorner_16 = Instance.new("UICorner")
local TextButton_9 = Instance.new("TextButton")
local UICorner_17 = Instance.new("UICorner")
local TextButton_10 = Instance.new("TextButton")
local UICorner_18 = Instance.new("UICorner")
local TextButton_11 = Instance.new("TextButton")
local UICorner_19 = Instance.new("UICorner")
local TextButton_12 = Instance.new("TextButton")
local UICorner_20 = Instance.new("UICorner")
local TextButton_13 = Instance.new("TextButton")
local UICorner_21 = Instance.new("UICorner")
local TextButton_14 = Instance.new("TextButton")
local UICorner_22 = Instance.new("UICorner")
local TextButton_15 = Instance.new("TextButton")
local UICorner_23 = Instance.new("UICorner")
local TextButton_16 = Instance.new("TextButton")
local UICorner_24 = Instance.new("UICorner")
local TextButton_17 = Instance.new("TextButton")
local UICorner_25 = Instance.new("UICorner")
local TextButton_18 = Instance.new("TextButton")
local UICorner_26 = Instance.new("UICorner")
local TextButton_19 = Instance.new("TextButton")
local UICorner_27 = Instance.new("UICorner")
local TextBox_2 = Instance.new("TextBox")
local UICorner_28 = Instance.new("UICorner")
local ImageLabel_3 = Instance.new("ImageLabel")
local TextButton_20 = Instance.new("TextButton")
local UICorner_29 = Instance.new("UICorner")
local TextButton_21 = Instance.new("TextButton")
local UICorner_30 = Instance.new("UICorner")
local TextButton_22 = Instance.new("TextButton")
local UICorner_31 = Instance.new("UICorner")
local TextButton_23 = Instance.new("TextButton")
local UICorner_32 = Instance.new("UICorner")

--Properties:

Scatsus.Name = "Scatsus"
Scatsus.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Scatsus.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

TextButton.Parent = Scatsus
TextButton.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BackgroundTransparency = 0.550
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.0902591497, 0, 0.45961538, 0)
TextButton.Size = UDim2.new(0.150000006, 0, 0.136000007, 0)
TextButton.Font = Enum.Font.FredokaOne
TextButton.Text = "Open"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 49.000
TextButton.TextWrapped = true

UICorner.Parent = TextButton

Frame.Parent = Scatsus
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.BackgroundTransparency = 0.550
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.283606648, 0, 0.817434371, 0)
Frame.Size = UDim2.new(0.516129017, 0, 0.113207549, 0)
Frame.Visible = false

INFO.Name = "INFO"
INFO.Parent = Frame
INFO.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
INFO.BackgroundTransparency = 0.550
INFO.BorderColor3 = Color3.fromRGB(0, 0, 0)
INFO.BorderSizePixel = 0
INFO.Position = UDim2.new(0.362977982, 0, -5.76117039, 0)
INFO.Size = UDim2.new(0.306018412, 0, 3.46717501, 0)

UICorner_2.Parent = INFO

TextLabel.Parent = INFO
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.345903993, 0, 0.0266072694, 0)
TextLabel.Size = UDim2.new(0.654095948, 0, 0.103566207, 0)
TextLabel.Font = Enum.Font.FredokaOne
TextLabel.Text = "ScatSus"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

TextLabel_2.Parent = INFO
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.296715289, 0, 0.102443427, 0)
TextLabel_2.Size = UDim2.new(0.566514969, 0, 0.136275783, 0)
TextLabel_2.Font = Enum.Font.FredokaOne
TextLabel_2.Text = "a nice keyless hub"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

ImageLabel.Parent = INFO
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(0.0306344759, 0, 0.0300387815, 0)
ImageLabel.Size = UDim2.new(0.315268636, 0, 0.233177572, 0)
ImageLabel.Image = "http://www.roblox.com/asset/?id=6403436054"

UICorner_3.Parent = ImageLabel

Frame_2.Parent = INFO
Frame_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BackgroundTransparency = 0.750
Frame_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0.0482167564, 0, 0.328585893, 0)
Frame_2.Size = UDim2.new(0.893711209, 0, 0.621688545, 0)

UICorner_4.Parent = Frame_2

ImageLabel_2.Parent = INFO
ImageLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_2.BorderSizePixel = 0
ImageLabel_2.Position = UDim2.new(0.0990352929, 0, 0.370431244, 0)
ImageLabel_2.Size = UDim2.new(0.803438127, 0, 0.254770339, 0)
ImageLabel_2.Image = "rbxassetid://15095116361"

TextLabel_3.Parent = ImageLabel_2
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(-0.00492020743, 0, 0, 0)
TextLabel_3.Size = UDim2.new(0.489932328, 0, 0.40043816, 0)
TextLabel_3.Font = Enum.Font.FredokaOne
TextLabel_3.Text = "Relleased!"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

UICorner_5.Parent = ImageLabel_2

TextLabel_4.Parent = ImageLabel_2
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Position = UDim2.new(0, 0, 0.265822768, 0)
TextLabel_4.Size = UDim2.new(0.999999344, 0, 0.734177232, 0)
TextLabel_4.Font = Enum.Font.FredokaOne
TextLabel_4.Text = "Hey Folks! We decided to rellease after many delays.  Update  everyweek"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14.000
TextLabel_4.TextWrapped = true

UICorner_6.Parent = Frame

EXECUTOR.Name = "EXECUTOR"
EXECUTOR.Parent = Frame
EXECUTOR.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
EXECUTOR.BackgroundTransparency = 0.550
EXECUTOR.BorderColor3 = Color3.fromRGB(0, 0, 0)
EXECUTOR.BorderSizePixel = 0
EXECUTOR.Position = UDim2.new(0.684161127, 0, -5.75918961, 0)
EXECUTOR.Size = UDim2.new(0.616651595, 0, 5.0569706, 0)

UICorner_7.Parent = EXECUTOR

TextBox.Parent = EXECUTOR
TextBox.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BackgroundTransparency = 0.700
TextBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0.024390243, 0, 0.168284789, 0)
TextBox.Size = UDim2.new(0.945121944, 0, 0.76375407, 0)
TextBox.Font = Enum.Font.FredokaOne
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox.TextSize = 14.000
TextBox.TextWrapped = true
TextBox.TextXAlignment = Enum.TextXAlignment.Left
TextBox.TextYAlignment = Enum.TextYAlignment.Top

UICorner_8.Parent = TextBox

TextButton_2.Parent = EXECUTOR
TextButton_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BackgroundTransparency = 0.700
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0.21622473, 0, 0.0256629121, 0)
TextButton_2.Size = UDim2.new(0.169130176, 0, 0.107628219, 0)
TextButton_2.Font = Enum.Font.FredokaOne
TextButton_2.Text = "Copy"
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 22.000
TextButton_2.TextWrapped = true

UICorner_9.Parent = TextButton_2

TextButton_3.Parent = EXECUTOR
TextButton_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BackgroundTransparency = 0.700
TextButton_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0.610533655, 0, 0.0256629121, 0)
TextButton_3.Size = UDim2.new(0.169130176, 0, 0.107628219, 0)
TextButton_3.Font = Enum.Font.FredokaOne
TextButton_3.Text = "Clear"
TextButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.TextScaled = true
TextButton_3.TextSize = 22.000
TextButton_3.TextWrapped = true

UICorner_10.Parent = TextButton_3

TextButton_4.Parent = EXECUTOR
TextButton_4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BackgroundTransparency = 0.700
TextButton_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(0.0231353007, 0, 0.0256629121, 0)
TextButton_4.Size = UDim2.new(0.169130176, 0, 0.107628219, 0)
TextButton_4.Font = Enum.Font.FredokaOne
TextButton_4.Text = "Execute"
TextButton_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.TextScaled = true
TextButton_4.TextSize = 22.000
TextButton_4.TextWrapped = true

UICorner_11.Parent = TextButton_4

TextButton_5.Parent = EXECUTOR
TextButton_5.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.BackgroundTransparency = 0.700
TextButton_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.BorderSizePixel = 0
TextButton_5.Position = UDim2.new(0.411346674, 0, 0.0256629121, 0)
TextButton_5.Size = UDim2.new(0.169130176, 0, 0.107628219, 0)
TextButton_5.Font = Enum.Font.FredokaOne
TextButton_5.Text = "Paste"
TextButton_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_5.TextScaled = true
TextButton_5.TextSize = 22.000
TextButton_5.TextWrapped = true

UICorner_12.Parent = TextButton_5

TextButton_6.Parent = Frame
TextButton_6.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_6.BackgroundTransparency = 1.000
TextButton_6.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_6.BorderSizePixel = 0
TextButton_6.Position = UDim2.new(0.0239827298, 0, 0.178327024, 0)
TextButton_6.Size = UDim2.new(0.0839350149, 0, 0.628525674, 0)
TextButton_6.Font = Enum.Font.FredokaOne
TextButton_6.Text = ""
TextButton_6.TextColor3 = Color3.fromRGB(254, 254, 254)
TextButton_6.TextScaled = true
TextButton_6.TextSize = 14.000
TextButton_6.TextWrapped = true

UICorner_13.Parent = TextButton_6

Scripthub.Name = "Scripthub"
Scripthub.Parent = Frame
Scripthub.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Scripthub.BackgroundTransparency = 0.550
Scripthub.BorderColor3 = Color3.fromRGB(0, 0, 0)
Scripthub.BorderSizePixel = 0
Scripthub.Position = UDim2.new(-0.375676095, 0, -5.75918961, 0)
Scripthub.Size = UDim2.new(0.723047733, 0, 4.73143435, 0)

UICorner_14.Parent = Scripthub

ScrollingFrame.Parent = Scripthub
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ScrollingFrame.BackgroundTransparency = 1.000
ScrollingFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScrollingFrame.BorderSizePixel = 0
ScrollingFrame.Position = UDim2.new(0.0125693623, 0, 0.269230843, 0)
ScrollingFrame.Size = UDim2.new(0.987430573, 0, 0.714196026, 0)

UIGridLayout.Parent = ScrollingFrame
UIGridLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout.CellPadding = UDim2.new(0, 10, 0, 10)
UIGridLayout.CellSize = UDim2.new(0, 60, 0, 60)

TextButton_7.Parent = ScrollingFrame
TextButton_7.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_7.BackgroundTransparency = 0.700
TextButton_7.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_7.BorderSizePixel = 0
TextButton_7.Position = UDim2.new(0.0544316135, 0, 0.0869652405, 0)
TextButton_7.Size = UDim2.new(0, 110, 0, 39)
TextButton_7.Font = Enum.Font.FredokaOne
TextButton_7.Text = "AutoPiano"
TextButton_7.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_7.TextScaled = true
TextButton_7.TextSize = 14.000
TextButton_7.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TextButton_7.TextWrapped = true

UICorner_15.Parent = TextButton_7

TextButton_8.Parent = ScrollingFrame
TextButton_8.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_8.BackgroundTransparency = 0.700
TextButton_8.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_8.BorderSizePixel = 0
TextButton_8.Position = UDim2.new(0.0544316135, 0, 0.0869652405, 0)
TextButton_8.Size = UDim2.new(0, 110, 0, 39)
TextButton_8.Font = Enum.Font.FredokaOne
TextButton_8.Text = "FE fly"
TextButton_8.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_8.TextScaled = true
TextButton_8.TextSize = 14.000
TextButton_8.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TextButton_8.TextWrapped = true

UICorner_16.Parent = TextButton_8

TextButton_9.Parent = ScrollingFrame
TextButton_9.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_9.BackgroundTransparency = 0.700
TextButton_9.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_9.BorderSizePixel = 0
TextButton_9.Position = UDim2.new(0.00632178225, 0, 0.00578444218, 0)
TextButton_9.Size = UDim2.new(0, 200, 0, 50)
TextButton_9.Font = Enum.Font.FredokaOne
TextButton_9.Text = "Vape Bedwars"
TextButton_9.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_9.TextScaled = true
TextButton_9.TextSize = 14.000
TextButton_9.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TextButton_9.TextWrapped = true

UICorner_17.Parent = TextButton_9

TextButton_10.Parent = ScrollingFrame
TextButton_10.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_10.BackgroundTransparency = 0.700
TextButton_10.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_10.BorderSizePixel = 0
TextButton_10.Position = UDim2.new(0.0544316135, 0, 0.0869652405, 0)
TextButton_10.Size = UDim2.new(0, 110, 0, 39)
TextButton_10.Font = Enum.Font.FredokaOne
TextButton_10.Text = "Ink Monster"
TextButton_10.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_10.TextScaled = true
TextButton_10.TextSize = 14.000
TextButton_10.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TextButton_10.TextWrapped = true

UICorner_18.Parent = TextButton_10

TextButton_11.Parent = ScrollingFrame
TextButton_11.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_11.BackgroundTransparency = 0.700
TextButton_11.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_11.BorderSizePixel = 0
TextButton_11.Position = UDim2.new(0.0544316135, 0, 0.0869652405, 0)
TextButton_11.Size = UDim2.new(0, 110, 0, 39)
TextButton_11.Font = Enum.Font.FredokaOne
TextButton_11.Text = "TP tool"
TextButton_11.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_11.TextScaled = true
TextButton_11.TextSize = 14.000
TextButton_11.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TextButton_11.TextWrapped = true

UICorner_19.Parent = TextButton_11

TextButton_12.Parent = ScrollingFrame
TextButton_12.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_12.BackgroundTransparency = 0.700
TextButton_12.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_12.BorderSizePixel = 0
TextButton_12.Position = UDim2.new(0.0544316135, 0, 0.0869652405, 0)
TextButton_12.Size = UDim2.new(0, 110, 0, 39)
TextButton_12.Font = Enum.Font.FredokaOne
TextButton_12.Text = "Simple admin"
TextButton_12.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_12.TextScaled = true
TextButton_12.TextSize = 14.000
TextButton_12.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TextButton_12.TextWrapped = true

UICorner_20.Parent = TextButton_12

TextButton_13.Parent = ScrollingFrame
TextButton_13.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_13.BackgroundTransparency = 0.700
TextButton_13.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_13.BorderSizePixel = 0
TextButton_13.Position = UDim2.new(0.0544316135, 0, 0.0869652405, 0)
TextButton_13.Size = UDim2.new(0, 110, 0, 39)
TextButton_13.Font = Enum.Font.FredokaOne
TextButton_13.Text = "Deathnote"
TextButton_13.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_13.TextScaled = true
TextButton_13.TextSize = 14.000
TextButton_13.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TextButton_13.TextWrapped = true

UICorner_21.Parent = TextButton_13

TextButton_14.Parent = ScrollingFrame
TextButton_14.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_14.BackgroundTransparency = 0.700
TextButton_14.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_14.BorderSizePixel = 0
TextButton_14.Position = UDim2.new(0.663787127, 0, 0.404910952, 0)
TextButton_14.Size = UDim2.new(0, 110, 0, 39)
TextButton_14.Font = Enum.Font.FredokaOne
TextButton_14.Text = "Korblox Headless"
TextButton_14.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_14.TextScaled = true
TextButton_14.TextSize = 14.000
TextButton_14.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TextButton_14.TextWrapped = true

UICorner_22.Parent = TextButton_14

TextButton_15.Parent = ScrollingFrame
TextButton_15.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_15.BackgroundTransparency = 0.700
TextButton_15.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_15.BorderSizePixel = 0
TextButton_15.Position = UDim2.new(0.280927122, 0, 0.735731363, 0)
TextButton_15.Size = UDim2.new(0, 96, 0, 27)
TextButton_15.Font = Enum.Font.FredokaOne
TextButton_15.Text = "Arsenal"
TextButton_15.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_15.TextScaled = true
TextButton_15.TextSize = 14.000
TextButton_15.TextWrapped = true

UICorner_23.Parent = TextButton_15

TextButton_16.Parent = ScrollingFrame
TextButton_16.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_16.BackgroundTransparency = 0.700
TextButton_16.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_16.BorderSizePixel = 0
TextButton_16.Position = UDim2.new(0.280927122, 0, 0.735731363, 0)
TextButton_16.Size = UDim2.new(0, 96, 0, 27)
TextButton_16.Font = Enum.Font.FredokaOne
TextButton_16.Text = "Anti fall"
TextButton_16.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_16.TextScaled = true
TextButton_16.TextSize = 14.000
TextButton_16.TextWrapped = true

UICorner_24.Parent = TextButton_16

TextButton_17.Parent = ScrollingFrame
TextButton_17.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_17.BackgroundTransparency = 0.700
TextButton_17.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_17.BorderSizePixel = 0
TextButton_17.Position = UDim2.new(0.777945757, 0, 0.365612239, 0)
TextButton_17.Size = UDim2.new(0, 96, 0, 27)
TextButton_17.Font = Enum.Font.FredokaOne
TextButton_17.Text = "Blade ball"
TextButton_17.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_17.TextScaled = true
TextButton_17.TextSize = 14.000
TextButton_17.TextWrapped = true

UICorner_25.Parent = TextButton_17

TextButton_18.Parent = ScrollingFrame
TextButton_18.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_18.BackgroundTransparency = 0.700
TextButton_18.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_18.BorderSizePixel = 0
TextButton_18.Position = UDim2.new(0.280927122, 0, 0.735731363, 0)
TextButton_18.Size = UDim2.new(0, 96, 0, 27)
TextButton_18.Font = Enum.Font.FredokaOne
TextButton_18.Text = "Fling"
TextButton_18.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_18.TextScaled = true
TextButton_18.TextSize = 14.000
TextButton_18.TextWrapped = true

UICorner_26.Parent = TextButton_18

TextButton_19.Parent = ScrollingFrame
TextButton_19.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_19.BackgroundTransparency = 0.700
TextButton_19.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_19.BorderSizePixel = 0
TextButton_19.Position = UDim2.new(0.280927122, 0, 0.735731363, 0)
TextButton_19.Size = UDim2.new(0, 96, 0, 27)
TextButton_19.Font = Enum.Font.FredokaOne
TextButton_19.Text = "MM2"
TextButton_19.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_19.TextScaled = true
TextButton_19.TextSize = 14.000
TextButton_19.TextWrapped = true

UICorner_27.Parent = TextButton_19

TextBox_2.Parent = Scripthub
TextBox_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextBox_2.BackgroundTransparency = 0.700
TextBox_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox_2.BorderSizePixel = 0
TextBox_2.Position = UDim2.new(0.0991661623, 0, 0.03877794, 0)
TextBox_2.Size = UDim2.new(0.796695948, 0, 0.135755181, 0)
TextBox_2.Font = Enum.Font.FredokaOne
TextBox_2.Text = ""
TextBox_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox_2.TextSize = 14.000

UICorner_28.Parent = TextBox_2

ImageLabel_3.Parent = TextBox_2
ImageLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_3.BackgroundTransparency = 1.000
ImageLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_3.BorderSizePixel = 0
ImageLabel_3.Size = UDim2.new(0.10474734, 0, 0.995015144, 0)
ImageLabel_3.Image = "http://www.roblox.com/asset/?id=11496279085"

TextButton_20.Parent = Frame
TextButton_20.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_20.BackgroundTransparency = 0.700
TextButton_20.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_20.BorderSizePixel = 0
TextButton_20.Position = UDim2.new(0.0172030758, 0, 0.137023419, 0)
TextButton_20.Size = UDim2.new(0.0821213871, 0, 0.711604655, 0)
TextButton_20.Font = Enum.Font.FredokaOne
TextButton_20.Text = "Close UI"
TextButton_20.TextColor3 = Color3.fromRGB(254, 254, 254)
TextButton_20.TextScaled = true
TextButton_20.TextSize = 14.000
TextButton_20.TextWrapped = true

UICorner_29.Parent = TextButton_20

TextButton_21.Parent = Frame
TextButton_21.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_21.BackgroundTransparency = 0.700
TextButton_21.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_21.BorderSizePixel = 0
TextButton_21.Position = UDim2.new(0.119359024, 0, 0.137023419, 0)
TextButton_21.Size = UDim2.new(0.0821213871, 0, 0.711604655, 0)
TextButton_21.Font = Enum.Font.FredokaOne
TextButton_21.Text = "Scripts"
TextButton_21.TextColor3 = Color3.fromRGB(254, 254, 254)
TextButton_21.TextScaled = true
TextButton_21.TextSize = 14.000
TextButton_21.TextWrapped = true

UICorner_30.Parent = TextButton_21

TextButton_22.Parent = Frame
TextButton_22.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_22.BackgroundTransparency = 0.700
TextButton_22.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_22.BorderSizePixel = 0
TextButton_22.Position = UDim2.new(0.221514985, 0, 0.137023419, 0)
TextButton_22.Size = UDim2.new(0.0821213871, 0, 0.711604655, 0)
TextButton_22.Font = Enum.Font.FredokaOne
TextButton_22.Text = "Update Logs"
TextButton_22.TextColor3 = Color3.fromRGB(254, 254, 254)
TextButton_22.TextScaled = true
TextButton_22.TextSize = 14.000
TextButton_22.TextWrapped = true

UICorner_31.Parent = TextButton_22

TextButton_23.Parent = Frame
TextButton_23.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_23.BackgroundTransparency = 0.700
TextButton_23.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_23.BorderSizePixel = 0
TextButton_23.Position = UDim2.new(0.327133834, 0, 0.137023419, 0)
TextButton_23.Size = UDim2.new(0.0821213871, 0, 0.711604655, 0)
TextButton_23.Font = Enum.Font.FredokaOne
TextButton_23.Text = "Executor"
TextButton_23.TextColor3 = Color3.fromRGB(254, 254, 254)
TextButton_23.TextScaled = true
TextButton_23.TextSize = 14.000
TextButton_23.TextWrapped = true

UICorner_32.Parent = TextButton_23

-- Scripts:

local function LSEZW_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	local startsize = UDim2.new(0.15, 0,0.136, 0)
	local hoversize = UDim2.new(0.16,0,0.17,0)
	
	script.Parent.MouseEnter:Connect(function()
		script.Parent:TweenSize(hoversize,Enum.EasingDirection.Out,Enum.EasingStyle.Sine,.25,true)
	end)
	
	script.Parent.MouseLeave:Connect(function()
		script.Parent:TweenSize(startsize,Enum.EasingDirection.Out,Enum.EasingStyle.Sine,.25,true)
	end)
end
coroutine.wrap(LSEZW_fake_script)()
local function RYZXR_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Frame.Visible = not script.Parent.Parent.Frame.Visible
	end)
end
coroutine.wrap(RYZXR_fake_script)()
local function UVKKVAK_fake_script() -- INFO.LocalScript 
	local script = Instance.new('LocalScript', INFO)

	local Frame = script.Parent
	
	Frame.Active = true
	Frame.Draggable = true
end
coroutine.wrap(UVKKVAK_fake_script)()
local function XDXQ_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	script.Parent.MouseButton1Down:Connect(function()
		script.Parent.Parent.TextBox.Text = tostring(game.Players.LocalPlayer.Character.HumanoidRootPart.Position)
	end)
end
coroutine.wrap(XDXQ_fake_script)()
local function PTAYH_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	local button = script.Parent
	local textbox = script.Parent.Parent.TextBox
	button.MouseButton1Click:Connect(function()
		textbox.Text = ""
	end)
end
coroutine.wrap(PTAYH_fake_script)()
local function LNVFLIV_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(script.Parent.Parent.TextBox.Text)()
	end)
end
coroutine.wrap(LNVFLIV_fake_script)()
local function PMDGK_fake_script() -- EXECUTOR.LocalScript 
	local script = Instance.new('LocalScript', EXECUTOR)

	local Frame = script.Parent
	
	Frame.Active = true
	Frame.Draggable = true
end
coroutine.wrap(PMDGK_fake_script)()
local function SWBN_fake_script() -- TextButton_6.LocalScript 
	local script = Instance.new('LocalScript', TextButton_6)

	script.Parent.MouseButton1Down:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(SWBN_fake_script)()
local function GVXQX_fake_script() -- TextButton_7.LocalScript 
	local script = Instance.new('LocalScript', TextButton_7)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/Madness676/3.2Lol/main/AutoPiano3-2.lua", true))()
	end)
end
coroutine.wrap(GVXQX_fake_script)()
local function URTZGRX_fake_script() -- TextButton_8.LocalScript 
	local script = Instance.new('LocalScript', TextButton_8)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/QGLvkvU7"))();
	end)
end
coroutine.wrap(URTZGRX_fake_script)()
local function QKQCUA_fake_script() -- TextButton_9.LocalScript 
	local script = Instance.new('LocalScript', TextButton_9)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))()
	end)
end
coroutine.wrap(QKQCUA_fake_script)()
local function KHWXDU_fake_script() -- TextButton_10.LocalScript 
	local script = Instance.new('LocalScript', TextButton_10)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe/main/obf_rTvXTs8F16D8D2oiLxZ62E1E9jT1we312yUyJr2h72Vwqr32l37rirU1S89hqRV7.lua.txt"))()
	end)
end
coroutine.wrap(KHWXDU_fake_script)()
local function NRPOK_fake_script() -- TextButton_11.LocalScript 
	local script = Instance.new('LocalScript', TextButton_11)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://pastefy.app/IpjIW7ZH/raw"))()
	end)
end
coroutine.wrap(NRPOK_fake_script)()
local function ZNSX_fake_script() -- TextButton_12.LocalScript 
	local script = Instance.new('LocalScript', TextButton_12)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet('https://pastebin.com/raw/3hDQcTaD'))()
	end)
end
coroutine.wrap(ZNSX_fake_script)()
local function VBPYRZ_fake_script() -- TextButton_13.LocalScript 
	local script = Instance.new('LocalScript', TextButton_13)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet(('h'..'t'..'t'..'p'..'s'..':'..'/'..'/'..'p'..'a'..'s'..'t'..'e'..'f'..'y'..'.'..'a'..'pp'..'/'..'G'..'o'..'K'..'x'..'Y'..'B'..'k'..'U'..'/'..'r'..'a'..'w'), true))()
	end)
end
coroutine.wrap(VBPYRZ_fake_script)()
local function EXSXT_fake_script() -- TextButton_14.LocalScript 
	local script = Instance.new('LocalScript', TextButton_14)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet('https://pastebin.com/raw/H5yx10Jq'))()
	end)
end
coroutine.wrap(EXSXT_fake_script)()
local function WHTDRO_fake_script() -- TextButton_15.LocalScript 
	local script = Instance.new('LocalScript', TextButton_15)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://pastebin.com/raw/1WVsaA7C"))()
	end)
end
coroutine.wrap(WHTDRO_fake_script)()
local function RAWOP_fake_script() -- TextButton_16.LocalScript 
	local script = Instance.new('LocalScript', TextButton_16)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/zephyr10101/AntiFall/main/Script"))()
	end)
end
coroutine.wrap(RAWOP_fake_script)()
local function LMMM_fake_script() -- TextButton_17.LocalScript 
	local script = Instance.new('LocalScript', TextButton_17)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/3345-c-a-t-s-u-s/-beta-/main/AutoParry.lua"))()
	end)
end
coroutine.wrap(LMMM_fake_script)()
local function PQBYMKQ_fake_script() -- TextButton_18.LocalScript 
	local script = Instance.new('LocalScript', TextButton_18)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet('https://gist.githubusercontent.com/1BlueCat/544f7efbe88235666b5b7add65b7344d/raw/f20804bb85542dcc3bc938982e1f05b7ff05cded/FE%2520Hat%2520Fling'))()
	end)
end
coroutine.wrap(PQBYMKQ_fake_script)()
local function UUPDPG_fake_script() -- TextButton_19.LocalScript 
	local script = Instance.new('LocalScript', TextButton_19)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet('https://raw.githubusercontent.com/ThatSick/HighlightMM2/main/Free'))()
	end)
end
coroutine.wrap(UUPDPG_fake_script)()
local function HLYAURZ_fake_script() -- Scripthub.LocalScript 
	local script = Instance.new('LocalScript', Scripthub)

	local scroll = script.Parent.ScrollingFrame -- CHANGE THIS TO YOUR SCROLLING FRAME
	local textBox = script.Parent.TextBox -- CHANGE THIS TO YOUR TEXT BOX
	
	textBox.Changed:Connect(function() -- when the text is changed
		local text = textBox.Text:lower() -- lowercase search bar text
		if text ~= "" then -- if it has text
			local buttons = scroll:GetDescendants() -- all of the buttons
			for _, button in pairs(buttons) do -- loops through the buttons
				if button:IsA("TextButton") then -- if it's a button
					local buttonText = button.Text:lower() -- lowercase button text
					if string.find(buttonText, text) then -- if search bar text is found in the button's text
						button.Visible = true -- shows button
					else -- otherwise
						button.Visible = false -- hides button
					end
				end
			end
		else -- if it's empty
			local buttons = scroll:GetDescendants() -- all buttons
			for _, button in pairs(buttons) do -- loops through buttons
				if button:IsA("TextButton") then -- if it's a button
					button.Visible = true -- shows button
				end
			end
		end
	end)
	
end
coroutine.wrap(HLYAURZ_fake_script)()
local function AABC_fake_script() -- Scripthub.LocalScript 
	local script = Instance.new('LocalScript', Scripthub)

	local Frame = script.Parent
	
	Frame.Active = true
	Frame.Draggable = true
end
coroutine.wrap(AABC_fake_script)()
local function URMYZA_fake_script() -- TextButton_20.LocalScript 
	local script = Instance.new('LocalScript', TextButton_20)

	script.Parent.MouseButton1Down:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(URMYZA_fake_script)()
local function KJMFUV_fake_script() -- TextButton_21.LocalScript 
	local script = Instance.new('LocalScript', TextButton_21)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Scripthub.Visible = not script.Parent.Parent.Scripthub.Visible
	end)
end
coroutine.wrap(KJMFUV_fake_script)()
local function FIVTL_fake_script() -- TextButton_22.LocalScript 
	local script = Instance.new('LocalScript', TextButton_22)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.INFO.Visible = not script.Parent.Parent.INFO.Visible
	end)
end
coroutine.wrap(FIVTL_fake_script)()
local function UNZZWVH_fake_script() -- TextButton_23.LocalScript 
	local script = Instance.new('LocalScript', TextButton_23)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.EXECUTOR.Visible = not script.Parent.Parent.EXECUTOR.Visible
	end)
end
coroutine.wrap(UNZZWVH_fake_script)()

