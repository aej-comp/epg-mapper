# epg-mapper

**epg-mapper** uses a Large Language Model (via AWS Bedrock) to match channels from an M3U playlist with entries in an Electronic Program Guide (EPG).

## Problem

Channel names in M3U playlists and EPG files often don't match exactly, which can lead to missing or incorrect program information.

## Solution

This tool uses an LLM to compare and match channels based on name similarity and context, improving the mapping between your playlist and the EPG.

## Features

- Match M3U channels with EPG entries, even if names differ  
- Uses AWS Bedrock to access a Large Language Model  
- Useful for IPTV and custom media setups
