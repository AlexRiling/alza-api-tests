# Alza Career API Test Suite

## Overview
Automated test suite for validating Alza career API job postings using .NET 8, NUnit, and RestSharp.

## Features
- ✅ Job description validation
- ✅ Work location verification
- ✅ Executive user information checks
- ✅ Retry logic with exponential backoff
- ✅ Mock data testing (demonstrates logic when API blocked)
- ✅ error handling

## Quick Start
1. Clone repository
2. Run: `dotnet restore`
3. Run: `dotnet test --logger "console;verbosity=detailed"`

## Test Coverage
- **Live API tests**: Test real endpoint when accessible
- **Mock data tests**: Verify validation logic always works
- **Error handling**: Graceful degradation for external issues

## Requirements Met
All assignment requirements implemented and tested.
