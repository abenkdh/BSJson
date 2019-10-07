# BSJson
 
        JsonObject jsObj = (JsonObject) new Gson().toJsonTree(new API());
        jsObj.addProperty("method_name", "HOME_SLIDER");
        BSJson bsJson = new BSJson.Builder(this)
                .setObject(jsObj)
                .setServer("")
                .load();
