
#Introduction

This is a rate control bar for uwp(universal windows platform)

You can use this listview with the follow codes:

<Page
    x:Class="DemoUWPRateControl.MainPage"
    xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
    xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
    xmlns:local="using:DemoUWPRateControl"
    xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
    xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
    xmlns:UWPRateControl="using:UWPRatingControl"
    mc:Ignorable="d">

    <Grid Background="{ThemeResource ApplicationPageBackgroundThemeBrush}">
        <UWPRateControl:RatingBar NumberOfStars="5" RatingValue="3" StarForegroundColor="#FF0078D7" HeightValue="30" />
    </Grid>
</Page>


For more information, to see the Demo in source.
